# notebooklm-dio
Projeto desenvolvido como parte do desafio da DIO sobre o uso do notebooklm como ferramenta de aprenndizagem.

## Contexto e Objetivos

**Assunto escolhido:** Fundamentos e conceitos intermediários da linguagem C++

**Por que esse tema?**
C++ é uma linguagem que já uso em projetos pessoais, na faculadade e no curso técnico que faço, porém, alguns tópicos, como gerenciamento de memória, são bem desafiadores.

**Objetivos de estudo:**
- [ ] Objetivo 1: Ser capaz de entender ponteiros, referência e gerenciamento de memória.
- [ ] Compreender os pilares de orientação a objetos em C++.
- [ ] Conhecer os principais recursos do STL (Standard Template Library).

## Curadoria de fontes
Fontes selecionadas e carregadas no notebook:

| 1 | cppreference.com — Pointers, References, Classes | Documentação oficial | https://en.cppreference.com/ |

| 2 | ISO C++ FAQ | Artigo | https://isocpp.org/faq |

| 3 | Learn C++ — capítulos sobre POO e memória dinâmica | Artigo/texto | https://www.learncpp.com/ |

| 4 | GCC — C++ Standards Support | Documentação oficial | https://gcc.gnu.org/projects/cxx-status.html |

| 5 | A Tour of C++ (capítulos de amostra) | PDF | site do autor/editora |

## Engenharia de prompt e "cicatrizes"

### Prompt 1
**Pergunta:**
> "Com base nas fontes selecionadas, explique quais as principais diferenças entre ponteiro e referências. Dê um exemplo de código para cada uma.

**Resposta (resumida):**
> A IA respondeu que as principais diferenças entre ponteiros e referências são: sintaxe de acesso, reatribuição, representação de ausência de objeto e passagem de parâmetros, explicando de forma não muito aprofundada cada uma das coisas, além de dar os exemplos que pedi.

---

### Prompt 2
**Pergunta:**
> "Quais os pilares da programação orientada a objetos em C++?"

**Resposta (resumida):**
> A IA respondeu que a POO em C++ gira em torno de classes, organizando-se e explicando os seguintes pilares e conceitos:
> 1. Encapsulamento e ocultamento de dados (Encapsulating/Data Hiding)
> 2. Abstração de tipos (Abstract Types)
> 3. Herança (Inheritance)
> 4. Polimorfismo (Polymorphism)

---

### Prompt 3
**Pergunta:**
> Quais os principais recursos do STL (Standard Template Library)

**Resposta (resumida):**
> A IA respondeu que a STL é uma estrutura genérica e extensível da biblioteca padrão do C++ projetada para conectar estruturas de dados a algoritmos de forma eficiente por meio de iteradores.
> Organizando-se em cinco componentes (ela explicou detlhadamente cada um deles):
> 1. Contêineres (Containers)
> 2. Iteradores (Iterators)
> 3. Algoritmos Genéricos (Algorithms)

---

## Miniguia de Estudo (Entrega Final)

### 🔹 Resumo Estruturado

**Ponteiros e Referências**
Ponteiros são variáveis que guardam endereços de memória, oferecendo flexibilidade (podem ser reatribuídos, aceitam `nullptr`) mas exigindo cuidado manual. Referências são "apelidos" para uma variável já existente, vinculadas permanentemente na inicialização, podem ser mais seguras, porém são flexíveis.

**Orientação a Objetos**
C++ segue os quatro pilares clássicos: encapsulamento (`public`/`private`/`protected`), herança (reaproveitamento de código entre classes), polimorfismo (via funções `virtual`) e abstração (classes abstratas e interfaces).

**Standard Template Library (STL)**
A STL é dividida em containers (`vector`, `list`, `map`, `set`), iteradores (que percorrem os containers de forma uniforme) e algoritmos genéricos (`sort`, `find`, `accumulate`), todos construídos com templates para funcionar com qualquer tipo de dado.

### 🔹 Glossário

| Termo | Definição |
|-------|-----------|
| Ponteiro | Variável que armazena o endereço de memória de outra variável |
| Referência | Um "apelido" vinculado permanentemente a uma variável já existente |
| Encapsulamento | Ocultar os detalhes internos de uma classe, expondo apenas o necessário |
| Polimorfismo | Capacidade de um objeto se comportar de formas diferentes dependendo do contexto, geralmente via funções `virtual` |
| Container (STL) | Estrutura de dados genérica da STL, como `vector`, `map` ou `set` |
| Iterador | Objeto que permite percorrer os elementos de um container de forma uniforme |

### 🔹 Prompts Reutilizáveis para Revisão

\```
1. "Explique [conceito de C++] com um exemplo de código comentado."
2. "Compare [feature A] e [feature B] em C++, com prós e contras de cada um."
3. "Quais erros comuns cometem iniciantes ao usar [tópico]? Cite exemplos de código incorreto e correto."
4. "Quais os principais métodos e casos de uso do container [nome do container] da STL?"
5. "Crie 5 perguntas de revisão sobre [tópico] em nível [coloce o nível], com respostas comentadas."
\```

---

## Ferramentas Utilizadas
- [NotebookLM](https://notebooklm.google.com/)
- cppreference.com, isocpp.org, learncpp.com, gcc.gnu.org, A Tour Of C++ como fontes de curadoria

## Como Usar Este Repositório
Este repositório documenta meu processo de estudo sobre C++ com apoio de IA. Sinta-se livre para explorar as fontes utilizadas, os prompts testados (incluindo os ajustes que fiz até obter boas respostas) e o miniguia final consolidado na seção acima.
