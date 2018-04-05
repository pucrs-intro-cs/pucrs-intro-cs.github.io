## Introdução a Ciência da Computação

<!-- You can use the [editor on GitHub](https://github.com/pucrs-intro-cs/pucrs-intro-cs.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.-->

<!-- Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files. -->

O cumprimento da disciplina busca dar ao aluno, ao final do semestre, condições de: 

1. Dominar as técnicas de pensamento computacional para a solução de problemas: abstração, reconhecimento e generalização de padrões, e projeto de algoritmos
2. Expressar computações através de uma linguagem de programação
3. Utilizar uma abordagem sistemática para organizar, descrever, testar e depurar algoritmos
4. Compreender de maneira introdutória o conceito de complexidade computacional
5. Aprender a utilizar ferramentas computacionais para visualizar e compreender dados

#### Instrutores em 2018/1:

- [Bernardo Copstein](https://github.com/bcopstein)
- [Alexandre Agustini](https://github.com/aagustini)
- [Felipe Meneguzzi](https://github.com/meneguzzi)


### Python Notebooks

#### Instruções de uso do [Jupyter Notebook](http://jupyter.org/)

1. Baixe os Notebooks (ou clone o repositório) no seu drive H
2. Execute os seguintes comandos no terminal (assumindo o [bash](https://pt.wikipedia.org/wiki/Bash))
```bash
cd ~/DriveH/
jupyter notebook
```
3. Acesse o browser e divirta-se

#### Notebooks para 2018/1

1. [Programas Sequenciais](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/1-Sequential%20Programs.ipynb)
2. [Programas Condicionais](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/2-Branching%20Programs.ipynb)
3. [Programas com Repetição](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/3-Iterative%20Programs.ipynb)
4. [Representação de Ponto Flutuante](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/4-Number%20Representation.ipynb)
5. [Aproximação e Convergência](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/5-Approximation%20and%20Bissection.ipynb)
6. [Strings e Subprogramação](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/6-Strings-and-Functions.ipynb)
7. [Funções, Módulos, e Arquivos](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/7-Functions-Modules-Files.ipynb)
8. [Recursão](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/8-Recursion.ipynb)
9. [Depuração](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/9-Testing-Debugging.ipynb)
10. [Tuplas](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/10-Tuples-Lists.ipynb)
11. [Lambda e Dicionários](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/11-Lambdas-Dictionaries.ipynb)
12. [Gráficos](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/12-Plotting.ipynb)
13. [Complexidade](https://github.com/pucrs-intro-cs/python-notebooks/blob/master/13-Complexity.ipynb)


### Instruções para o uso do Git

- [Hello World do Git](https://guides.github.com/activities/hello-world/): Explicações básicas sobre Git, Github e os commandos básicos deste tipo de sistema de versionamento
- [Como configurar o Git](https://help.github.com/articles/set-up-git/)
- [Como criar um repositório Git](https://help.github.com/articles/create-a-repo/)
- [Como ramificar um repositório existente](https://help.github.com/articles/fork-a-repo/)
- [Interação Social no Github](https://help.github.com/articles/be-social/)

#### Ciclo básico de uso

1. Clonar um repositório pela primeira vez (troque ```<seu repo>``` pelo nome do seu repositório: 
```bash
git clone <seu repo>
```

2. Sincronizar mudanças para a máquina local (assumindo pasta onde está o repositório):
```bash
cd python-notebooks
git pull
```

3. Depositar mudanças feitas localmente e sincronizar com o remoto
```
git commit -m "Minha mensagem"
git push orgin/master
```


### Lista de Leituras

Data           |   Aula    |    Leitura  | Sala
--------------- | ---------- | ------------  | ---------
06/03/2018 | Apresentação da disciplina                                                            |   [Textbook: Chapter 1][Introduction to Computation and Programming Using Python]  | 
08/03/2018 | Estratégia para solução de problemas                                                  |   [Think like a programmer: Chapter 1][Think Like a Programmer: An Introduction to Creative Problem Solving]  | 
13/03/2018 | Elementos básicos de um programa                                                     | Sections 2.1 and 2.2 of [Textbook: Chapter 2][Introduction to Computation and Programming Using Python]   | Laboratório - 310
15/03/2018 | Exercícios programas sequenciais                                                      |  Sections 2.1 and 2.2 of [Textbook: Chapter 2][Introduction to Computation and Programming Using Python]   | Laboratório - 309
20/03/2018 | Programas condicionais                               | Sections 2.2 and 2.3 and 2.4 of [Textbook: Chapter 2][Introduction to Computation and Programming Using Python]   | Laboratório - 309
22/03/2018 | Programas com repetição                                        |  Sections 2.2 and 2.3 and 2.4 (mostly 2.4) of [Textbook: Chapter 2][Introduction to Computation and Programming Using Python]  | Laboratório - 309
27/03/2018 | Exercício valendo nota                                                                |    | Laboratório - 309
03/04/2018 | Representação de valores em ponto flutuante                               | Section 3.4 of [Textbook: Chapter 3][Introduction to Computation and Programming Using Python]   | 
05/04/2018 | Exercícios sobre representação de valores em ponto flutuante                          | Section 3.4 of [Textbook: Chapter 3][Introduction to Computation and Programming Using Python]   | Laboratório - 309
10/04/2018 | Algoritmos de aproximação e convergência                                     |  [Textbook: Chapter 3][Introduction to Computation and Programming Using Python]  | Laboratório - 310
12/04/2018 | Exercícios sobre algoritmos de aproximação e convergência                             |    | Laboratório - 309
17/04/2018 | Strings                                                |  Section 2.3 of [Textbook: Chapter 2][Introduction to Computation and Programming Using Python] and Section 4.1 of [Textbook: Chapter 4][Introduction to Computation and Programming Using Python]  | Laboratório - 309
19/04/2018 | Funções                                  |   Sections 4.1, 4.2, 4.4, 4.5 and 4.6 of [Textbook: Chapter 4][Introduction to Computation and Programming Using Python]  | Laboratório - 310
24/04/2018 | Recursão                                                       |  Section 4.3 of [Textbook: Chapter 4][Introduction to Computation and Programming Using Python]  | Laboratório - 309
26/04/2018 | Prova P1                                                                              |    | 
03/05/2018 | Correção da P1                                                                        |    | 
08/05/2018 | Teste e depuração                                                             |  [Textbook: Chapter 6][Introduction to Computation and Programming Using Python]  | Laboratório - 309
10/05/2018 | Tuplas e listas                                          |  Sections 5.1 and 5.3 of [Textbook: Chapter 5][Introduction to Computation and Programming Using Python]  | Laboratório - 309
15/05/2018 | Exercícios sobre tuplas e listas                                                      |    | Laboratório - 309
17/05/2018 | Funções lambda                                                 | Section 5.4 of [Textbook: Chapter 5][Introduction to Computation and Programming Using Python]   | Laboratório - 310
22/05/2018 | Dicionários             | Sections 5.4 and 5.5 of [Textbook: Chapter 5][Introduction to Computation and Programming Using Python]   | Laboratório - 309
24/05/2018 | Exercícios sobre strings, listas, dicionários e tuplas                                |    | Laboratório - 309
29/05/2018 | Exercício valendo nota                                                                |    | Laboratório - 309
05/06/2018 | Traçado de gráficos                                                     |   [Textbook: Chapter 11][Introduction to Computation and Programming Using Python]  | Laboratório - 309
07/06/2018 | Exercícios sobre arquivos e traçado de gráficos                                       |    | Laboratório - 309
12/06/2018 | Introdução a complexidade de algoritmos                                               |  [Textbook: Chapter 9][Introduction to Computation and Programming Using Python]  | Laboratório - 310
14/06/2018 | Exercícios sobre complexidade de algoritmos                                           |    | Laboratório - 309
19/06/2018 | Exercícios sobre complexidade de algoritmos                                           |    | Laboratório - 309
21/06/2018 | Exercício valendo nota                                                                |    | Laboratório - 309
26/06/2018 | Dúvidas para prova                                                                    |    | 
28/06/2018 | Prova P2                                                                              |    | 
03/07/2018 | Prova PS                                                                              |    | 
05/07/2018 | Dúvidas para G2                                                           

#### Livros Texto

[Introduction to Computation and Programming Using Python]: [https://github.com/y0m0/MIT.6.00.1x/raw/master/Introduction.to.Computation.and.Programming.Using.Python.2nd.Edition.pdf]
[Think Like a Programmer: An Introduction to Creative Problem Solving]: [https://www.amazon.com/Think-Like-Programmer-Introduction-Creative/dp/1593274246/ref=sr_1_2?ie=UTF8&qid=1517942703&sr=8-2&keywords=THINK+LIKE+A+PROGRAMMER]


<!-- ### Markdown

TBD
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/). -->


<!-- Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out. -->
