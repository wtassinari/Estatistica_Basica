# Disciplinas de Estatística Básica e Introdução à Bioestatística 

**Prof. Wagner Tassinari (DEMAT/UFRRJ)**

*wtassinari@gmail.com*


Repositório das disciplinas de Estatística Básica e Introdução à Bioestatística - 2020-1 (DEMAT/UFRRJ)

## OBJETIVO DAS DISCIPLINAS: 

- Introduzir os conceitos básicos de estatística dando maior ênfase às aplicações nas diversas ciências.

- O curso será composto de atividade **síncronas**, são atividades baseadas em encontros remotos professor-alunos on line, e  das atividades **assíncronas**, são atividades que poderam ser feitas pelos alunos sem a presença do professor, por exemplo: Leitura do material bibliográfico, videoaulas, listas de exercícios e trabalhos em grupo. As aulas síncronas serão feitas via plataforma Google Meet todas à terças e quintas das 9h às 10:30h, durante o período do curso. O link para o acesso as aulas estará disponível ni sistema SIGAA - UFRRJ no tópico referente a data da aula.

### PROGRAMA:

- Introdução à Estatística

- Apresentação dos dados em Tabelas

- Apresentação dos dados em Gráficos

- Medidas de Tendência Central

- Medidas de Dispersão

- Associação entre duas Variáveis

- Introdução à Probabilidade

- Variáveis Aleatórias Discretas e Contínuas

- Introduão à Inferência Estatística

- Intervalos de Confiança


## AVALIAÇÃO:

- P1 – 02/02/2021 

- P2 – 29/04/2021

- Segunda Chamada – 04/05/2021

- Optativa – 06/05/2021


$\frac{P1+P2+2.P3}{4} \geq 5 \longrightarrow Aprovado$

- OBS: A nota da prova optativa substuirá a menor nota e a média será recalculada utilizando a mesma fórmula.


## Bibliografias

### Bibliografia Básica


-  Wilton O. Bussab; Pedro A. Morettin. **Estatística Básica**. Editora Saraiva

-  Sonia Vieira. **Introdução à Bioestatística**. Editora Elsevier

-  Diógenes e Adriana Souza. **Apostila de Estatística Básica** (Imprensa)


### Bibliografia Sugerida

- [Vu, J; Harrington, D. **Introductory Statistics for the Life and Biomedical Sciences**, 1ª edição. 2020.](https://leanpub.com/biostat)

- [Diez, DM; Barr, C D; Çetinkaya-Rundel M. **OpenIntro Statistics**, 3ª edição. 2015.](https://leanpub.com/openintro-statistics)



# Cronograma do curso:


| Aulas |             Descrição             | Data  |      |      Aulas      |                    Descrição                     | Data  |
| :---: | :-------------------------------: | :---: | ---- | :-------------: | :----------------------------------------------: | :---: |
|   -   |    Apresentação da  Disciplina    | 02/02 | ---- |        8        |            Introdução à Probabilidade            | 23/03 |
|   1   |         Conceitos Básicos         | 04/02 |   :   |        8        |            Introdução à Probabilidade            | 25/03 |
|   1   |         Conceitos Básicos         | 09/02 |    :  |        9        |               Variáveis Aleatórias               | 30/03 |
| 2 e 3 |        Tabelas e Gráficos         | 11/02 |    :  |        9        |               Variáveis Aleatórias               | 01/04 |
| 2 e 3 |        Tabelas e Gráficos         | 18/02 |     : |       10        | Distribuições de Probabilidade para VA discretas | 06/04 |
|   4   |        Medidas de Posição         | 23/02 |      |       10        | Distribuições de Probabilidade para VA discretas | 08/04 |
|   4   |        Medidas de Posição         | 25/02 |      |       11        | Distribuições de Probabilidade para VA contínuas | 13/04 |
| 5 e 6 | Medidas de Dispersão e Assimetria | 02/03 |      |       11        | Distribuições de Probabilidade para VA contínuas | 15/04 |
| 5 e 6 | Medidas de Dispersão e Assimetria | 04/03 |      |       12        |       Introdução à Inferência Estatística        | 20/04 |
|   7   |       Análise Bidimensional       | 09/03 |      |       12        |       Introdução à Inferência Estatística        | 22/04 |
|   7   |       Análise Bidimensional       | 11/03 |      |        -        |                     Revisão                      | 27/04 |
|   -   |              Revisão              | 16/03 |      |      P2      |                        -                         | 29/04 |
| P1 |                 -                 | 18/03 |      | Segunda Chamada |                        -                         | 04/05 |
| - |                 -                 | - |      | Optativa |                        -                         | 06/05 |

### **Aula 1:** Apresentação da disciplina

- Nessa aula síncrona será apresentado esse novo formato da disciplina (conteúdo e dinâmica das aulas). Uma breve apresentação de como iremos utilizar a ferramenta do R no contexto da disciplina. Introdução e planejamento da coleta de dados.

- Para a aula síncrona deste dia, é sugerido de que os alunos já tenham feito a instalação do pacote estatístico R da interface gráfica RStudio baixado e instalado a biblioteca Rcmd referente a interface gráfica Rcommander, como mostrado nas videoaulas e no material complementar disponíveis nessa página.

| Atividades  |       Tipo de Atividade                                             |
| :---------: | ------------------------------------------------------------ |
| Assincrona | [Video mostrando sites para download do R](https://www.youtube.com/watch?v=waiNuVtj9-U) |
| Assincrona | [Vídeo para instalação e carregamento de pacotes no R](https://www.youtube.com/watch?v=_7KxO0QIwP4) |
| Assincrona | [Vídeo resumido para instalação do R e do Rcomander no Windows](https://www.youtube.com/watch?v=UsjmoW9zrbg) |
| Sincrona | [Slide da aula 1](https://www.dropbox.com/s/dx5jtz2ezkzxvdo/Apresentacao.pdf?dl=0) |


### **Aula 2:** Análise Exploratória de Dados (AED) - Parte 1

- Nessa aula serão apresentados conceitos sobre construção de tabelas e gráficos de acordo com o contexto do problema e tipos de variáveis envolvidas. O conteúdo será abordado de forma assíncrona (videoaulas e lista de exercícios). 

- É sugerido que os alunos tentem fazer os exercícios propostos nos slides das aulas e a lista de exercícios como ferramenta auxiliar para o aprendizado. 

| Atividade  |       Tipo de Atividade                                       | Links|
| :---------: | ------------------------------------------------------------ | ----- |
| Assincrona | Videoaula AED 1  |  [link](https://www.dropbox.com/s/3ix7wggll8pdk7e/AED1.mp4?dl=0)  |
| Assincrona | Slides da aula AED 1  |  [link](https://www.dropbox.com/s/41uyl6nn0s89h27/Aula1_IntEpi_EDA.pdf?dl=0) |
| Assincrona | Videoaula AED 2 |  [link](https://www.dropbox.com/s/34sg6gzc28bj7lu/AED2.mp4?dl=0)  |
| Assincrona | Slides da aula AED 2 |  [link](https://www.dropbox.com/s/h4jgssrfufkrklu/Aula2_IntEpi_EDA.pdf?dl=0)  |
| Assincrona | Lista de exercícios |  [link](https://www.dropbox.com/s/xvssztikg51yqv4/Lista01_2020.pdf?dl=0)  |
| Síncrona | Planilha com exercícios |  [link](https://www.dropbox.com/scl/fi/6ooq1h2k1k4ttmq082ixh/Exercicio_aula_2.xlsx?dl=0&rlkey=eg8sixxoakm7spd4xskfdxqqx)  |
| Síncrona | Slides elaboração de tabelas e gráficos pelo Rcommander |  [link](https://www.dropbox.com/s/1ord3mdx1ju7mmp/Aula-2_sincrona.pdf?dl=0)  |

- Essas atividades listadas abaixo, são atividades voltadas para a importação e criação de bancos de dados através da interface Rcommander

| Vídeos Rcommander  |       Importando e criando banco de dados pelo Rcommander     | Links|
| :---------: | ------------------------------------------------------------ | ----- |
| Vídeo 1 | Abrindo o Rcommander a partir do Rstudio e utilizando como calculadora  |  [link](https://www.dropbox.com/s/wppqrvr898ac5qx/viodeaulaRComander1.mp4?dl=0)  |
| Vídeo 2| Lendo o banco de dados birthwt a paritr da biblioteca MASS  |  [link](https://www.dropbox.com/s/aqi01ndi2kxfrx3/viodeaulaRComander2.mp4?dl=0) |
| Vídeo 3 | Lendo o banco de dados birthwt a paritr de um arquivo em excel  |  [link](https://www.dropbox.com/s/cr7158jcn74sb71/viodeaulaRComander3.mp4?dl=0)  |
| Vídeo 4 | Criando um banco de dados a partir do RCommander  |  [link](https://www.dropbox.com/s/3c74jtocqff3zhy/viodeaulaRComander4.mp4?dl=0)  |



### **Aula 3:** Análise Exploratória de Dados - Parte 2

- Nessa aula serão apresentados conceitos sobre medidas-resumo (medidas de tendência central, posição e dispersão. O conteúdo será abordado de forma teórica, com exercícios e prática em R. 


| Atividade  |       Tipo de Atividade                                       | Links|
| :---------: | ------------------------------------------------------------ | ----- |
| Assincrona | Videoaula AED 3 - Parte 1  |  [link](https://www.dropbox.com/s/bahzsbtaacbrm7f/AED3_1.mp4?dl=0)  |
| Assincrona | Videoaula AED 3 - Parte 2 |  [link](https://www.dropbox.com/s/9qlv2ppadc532gm/AED3_2.mp4?dl=0)  |
| Assíncrona | Slides da aula 3 - Parte 1 | [link](https://www.dropbox.com/s/s51hsz7u4rrjrp0/Aula3_parte1_IntEpi_EDA.pdf?dl=0)   |
| Assíncrona | Slides da aula 3 - Parte 2 | [link](https://www.dropbox.com/s/3m58ytifnom8yuo/Aula3_parte2_IntEpi_EDA.pdf?dl=0)   |
| Assincrona | Videoaula AED 4 |  [link](https://www.dropbox.com/s/46ygc2zqnkwdpsm/AED4.mp4?dl=0)  |
| Assíncrona | Slides da aula 4  | [link](https://www.dropbox.com/s/4jqs5cpsnc37upr/Aula4_IntEpi_EDA.pdf?dl=0)  |
| Síncrona | Planilha com exercícios |  [link](https://www.dropbox.com/scl/fi/cb3no1nu46spcokjb3prw/Exercicio_aula_3.xlsx?dl=0&rlkey=bx3b2sz0oygqhbzvzpq02sa72)  |
| Síncrona | Slides de estatísticas descritivas pelo Rcommander |  [link](https://www.dropbox.com/s/mibjopyot9ftye4/Aula-3_sincrona.pdf?dl=0)  |
