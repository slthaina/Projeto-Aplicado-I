**PROJETO DE ANÁLISE DO IDEB E DESIGUALDADE EDUCACIONAL EM SÃO PAULO**

**Integrantes do Grupo**

Karla Maria Ramos da Silva (10441405)

Thainá Silva Leite (10730503)

**Objetivo:** Este projeto busca investigar como o Índice de Desenvolvimento da Educação Básica (IDEB) varia entre os diferentes distritos da cidade de São Paulo, analisando sua evolução ao longo do tempo e identificando quais fatores socioeconômicos podem estar correlacionados com essa variação.

**Hipótese:**
Existe uma correlação significativa entre o desempenho escolar, medido pelo IDEB, e os indicadores socioeconômicos dos distritos de São Paulo, especialmente os componentes de renda e educação do IDHM. Espera-se que regiões com menor desenvolvimento humano apresentem IDEB mais baixos.

**Secretaria Municipal de Educação de São Paulo (SME-SP)**

**Descrição:** A organização escolhida para este estudo é a Secretaria Municipal de Educação de São Paulo (SME-SP), responsável pela gestão da rede municipal de ensino na cidade de São Paulo. Segundo a SME-SP, “a Secretaria Municipal de Educação de São Paulo é responsável pela formulação e implementação de políticas públicas educacionais, garantindo o acesso, a permanência e a aprendizagem dos estudantes” (SME-SP, 2025a). A SME-SP administra escolas de educação infantil, ensino fundamental e programas educacionais voltados para o desenvolvimento da qualidade de ensino (SME-SP, 2025).

**Fonte e Dados**
**Apresentação dos Dados (Metadados):**  Os principais metadados dos conjuntos de dados utilizados incluem:
Ano de Referência: Ano em que o IDEB foi calculado.
Código da Escola: Identificação única da escola na base de dados.
Nome da Escola: Nome oficial da unidade de ensino.
Prefeitura Regional: Divisão administrativa que pode agrupar um ou mais bairros. 
Nota IDEB: Índice de Desenvolvimento da Educação Básica da escola.
Indicadores Socioeconômicos: O índice adotado é o IDHM (Índice de Desenvolvimento Humano Municipal), com foco nos componentes de renda e educação.

**Metodologia:**
Os dados do IDEB e do IDHM foram coletados de plataformas públicas da Prefeitura de São Paulo e do IBGE. A análise exploratória incluiu a verificação de tipos de dados, valores ausentes, duplicações e estatísticas descritivas (média, mediana, desvio padrão, etc.).
Foram utilizadas visualizações como histogramas, tabelas de frequência e boxplots para observar padrões, distribuições e outliers. As correlações entre variáveis foram analisadas por meio de matrizes de correlação e mapas de calor.
Devido à limitação temporal dos dados do IDHM, projetou-se o índice para 2020 com modelos linear e exponencial. Estão previstas análises inferenciais, como regressão e ANOVA, além da aplicação de modelos preditivos para identificar fatores associados ao desempenho escolar.

**Requisitos Técnicos / Ambiente de Desenvolvimento:**
Este projeto foi desenvolvido com os seguintes recursos:
Python 3.13
Jupyter Notebook

Bibliotecas principais:
pandas
numpy
matplotlib
seaborn
os (biblioteca padrão do Python)

**Estrutura do Repositório**
- DOCS: Contém documentos relevantes do projeto, como relatórios finais, glossário, e resumos das análises realizadas.
- DATA: Armazena as bases de dados utilizadas no projeto, no formato .xls, .csv e outros formatos, se necessário.
- NOTEBOOKS: Contém os Jupyter Notebooks com os scripts de análise exploratória e manipulação de dados.
- RESULTS: Inclui o resultado final do projeto, como relatórios gerados e datasets tratados e linkados.
- VÍDEOS: Armazena a apresentação final do projeto, explicando os insights e resultados obtidos.

