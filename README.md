# FLEXBOX
#### CONTAINERS 
- **display: flex;**
  Inicia o container. 
- **flex-direction: row;**
  Direção dos elementos-filhos. Por padrão, em linhas.
	- *column, row-reverse, column-reverse*
- **flex-warp: no-wrap;**
  Define se os elementos terão quebra de linha ao chegar no tamanho máximo do container. Por padrão, sem quebra.
	- *warp, wrap-reverse*
- **flex-flow: row wrap;**
  Forma resumida de escrever o flex-direction e o flex-wrap. 
  
#### ALINHAMENTOS CONTAINER
- **justify-content: flex-start;**
  Alinhamento horizontal. Por padrão, ao início do container.
	- *flex-end, center, space-between, space around*
- **align-items: stretch;**
  Alinhamento vertical. Por padrão, define que os itens cresçam igualmente.
	- *flex-start, flex-end, center, baseline (baseado no conteúdo de cada item)*
- **align-content: stretch;**
  Alinhamento vertical (quando em multi-line ou seja, quando tiverem uma quebra). Por padrão, define que os itens cresçam igualmente.
	-* flex-start, flex-end, center, space-between, space-around, stretch*

#### ITEMS 
- **order;**
  Altera a ordem dos itens. Por padrão, ao início do container.
	-* .article_1 { order: 2; }*
- **align-self: auto;**
  Alinhamento individual do item, vertical (quando o flex-direction: row), horizontal (quando o flex-direction: column). Por padrão, ao início do container.
	- *flex-start, flex-end, center, baseline, stretch *
- **flex-grow: 0;**
  Largura dos itens dentro do container. Padrão é 0 (zero). Pode-se definir um tamanho para cada item individualmente.
	- *.article_1 { flex-grow: 1; }*
	- *.article_2 { flex-grow: 3; } //3x maior que o article_1*
- **flex-basis: 0;**
  Largura inicial de cada item. Padrão é 0 (zero, todos do mesmo tamanho). 
	- flex-basis: 20px;
- **flex-shrink: 0;**
  Relacionado a capacidade de redução do item.
	- *flex-start, flex-end, center, baseline, stretch *
- **flex: 1 2 300px;**
  Forma resumida de escrever o flex-grow, flex-shrink, flex-basis.
  
  
  ### LINK
  https://raillen.github.io/hotel-paraiso-flexbox/
