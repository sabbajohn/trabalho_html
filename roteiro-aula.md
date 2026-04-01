# Roteiro de Aula - Equipe 1

## Tema
Introducao ao HTML com foco em estrutura da pagina, navegador e DevTools.

## Duracao Total
1h15min

## Objetivo da Aula
Ao final da apresentacao, a turma deve conseguir:

* entender o esqueleto basico de um arquivo HTML
* reconhecer a funcao de tags simples como `html`, `head`, `body`, `h1`, `p`, `a`, `img`, `ul` e `li`
* perceber como as tags alteram a estrutura da pagina no navegador
* usar o DevTools para inspecionar, editar e testar pequenas mudancas em tempo real

## Estrategia
A aula deve ser curta na teoria e forte na demonstracao pratica. Como parte da turma ainda nao domina VS Code e Git, a abordagem sera:

* 5 a 10 minutos de contextualizacao sobre ferramentas
* restante do tempo com navegador aberto, codigo simples e DevTools
* participacao constante da turma com pequenas tarefas e perguntas curtas

## Materiais Necessarios
* navegador aberto
* DevTools pronto para uso
* VS Code aberto apenas para mostrar o arquivo HTML e CSS
* arquivo da apresentacao funcionando localmente

## Divisao do Tempo

### 1. Abertura e alinhamento - 5 min
Objetivo:
explicar rapidamente a proposta da aula e tirar a pressao inicial de quem nao conhece nada.

Fala sugerida:
"A ideia hoje nao e decorar tags. E entender como o HTML organiza uma pagina e ver isso funcionando ao vivo no navegador."

Perguntas para envolver a turma:
* quem ja abriu o inspecionar elemento alguma vez?
* quem ja mexeu em HTML, mesmo que bem pouco?

### 2. Ferramentas basicas: navegador, VS Code e Git - 8 min
Objetivo:
dar contexto sem transformar isso no foco da aula.

Pontos para falar:
* o navegador mostra o resultado final da pagina
* o VS Code e o editor onde escrevemos o codigo
* o DevTools ajuda a enxergar e testar mudancas no HTML e no CSS
* o Git serve para versionar o projeto e trabalhar em equipe, mas hoje ele nao sera o foco

Mensagem importante:
nao aprofundar comandos de Git. Apenas explicar o suficiente para nao deixar a turma perdida.

### 3. Esqueleto basico do HTML - 10 min
Objetivo:
mostrar que toda pagina comeca com uma estrutura simples.

Demonstracao:
* abrir o arquivo HTML
* mostrar `<!DOCTYPE html>`, `html`, `head` e `body`
* explicar rapidamente o que vai no `head` e o que vai no `body`

Participacao da turma:
* pedir para alguem apontar qual parte da pagina deve aparecer na aba do navegador
* perguntar onde entra o conteudo visivel: `head` ou `body`

Mini tarefa:
pedir para a turma prever o que acontece se mudarmos o conteudo da tag `title`

### 4. Primeiras tags visiveis - 12 min
Objetivo:
mostrar como o navegador responde a mudancas simples.

Demonstracao:
* criar ou editar um `h1`
* criar ou editar um `p`
* inserir um `a`
* inserir uma lista com `ul` e `li`

Pequenos desafios para a turma:
* "o que acontece se eu trocar `h1` por `h2`?"
* "como adicionamos mais um item na lista?"
* "o que muda se o link nao tiver `href`?"

Formato dinamico:
pedir respostas antes de executar a alteracao.

### 5. DevTools: inspecionando a estrutura - 15 min
Objetivo:
fazer a turma enxergar o HTML como estrutura da pagina.

Demonstracao:
* abrir o DevTools
* usar "Inspecionar" em um titulo
* mostrar o elemento correspondente na aba Elements
* destacar a relacao entre o bloco visual e a tag no codigo

Pequenos desafios:
* localizar no DevTools a tag do titulo principal
* localizar um link
* localizar um item da lista

Perguntas boas para manter a turma ativa:
* "qual tag voces acham que corresponde a esse texto?"
* "onde esta esse paragrafo dentro da estrutura?"

### 6. Editando ao vivo no DevTools - 15 min
Objetivo:
mostrar que o navegador permite testar mudancas instantaneamente.

Demonstracao:
* editar um texto direto na aba Elements
* adicionar um novo item de lista
* alterar um atributo `href`
* alterar o `alt` de uma imagem

Pequenos desafios:
* pedir para um colega sugerir um novo titulo
* pedir para outro sugerir um item extra na lista
* perguntar qual atributo descreve a imagem para acessibilidade

Mensagem central:
o DevTools nao substitui o codigo-fonte, mas e excelente para aprender, testar e depurar.

### 7. CSS rapido pelo DevTools - 7 min
Objetivo:
mostrar que a estrutura e o estilo caminham juntos, mas que hoje o foco principal e HTML.

Demonstracao:
* mudar a cor de um titulo na aba Styles
* desativar e reativar uma regra CSS
* mostrar rapidamente diferenca entre estrutura HTML e aparencia CSS

Pergunta para a turma:
* "o que mudou aqui: a estrutura da pagina ou so a aparencia?"

### 8. Fechamento com revisao e fixacao - 3 min
Objetivo:
encerrar sem correria e reforcar o aprendizado.

Revisao curta:
* HTML organiza a estrutura
* navegador interpreta e exibe
* DevTools ajuda a entender, testar e corrigir

Pergunta final:
* "se voces precisassem descobrir qual tag forma uma parte da pagina, qual ferramenta usariam?"

## Resumo do Cronograma
* 5 min - abertura
* 8 min - ferramentas basicas
* 10 min - esqueleto do HTML
* 12 min - primeiras tags visiveis
* 15 min - DevTools e estrutura
* 15 min - edicao ao vivo no DevTools
* 7 min - CSS rapido
* 3 min - fechamento

Total: 75 min

## Dicas Para Nao Se Perder Durante a Aula
* manter o navegador aberto o maior tempo possivel
* evitar longas explicacoes teoricas sem demonstracao
* sempre perguntar antes de executar uma mudanca
* usar exemplos simples e visiveis
* se a turma travar, retomar com titulo, paragrafo e lista

## Plano B
Se o tempo apertar:

* reduzir a parte de ferramentas para 5 minutos
* simplificar a parte de CSS
* priorizar `h1`, `p`, `a`, `ul`, `li` e DevTools

Se sobrar tempo:

* abrir uma imagem com `img`
* mostrar diferenca entre editar no arquivo e editar no DevTools
* propor um desafio final de 2 minutos para a turma sugerir mudancas
