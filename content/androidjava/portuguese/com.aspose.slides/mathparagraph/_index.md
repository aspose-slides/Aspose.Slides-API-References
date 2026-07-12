---
title: MathParagraph
second_title: Referência da API Java do Aspose.Slides para Android
description: Parágrafo matemático que é um contêiner para blocos matemáticos IMathBlock
type: docs
url: /pt/com.aspose.slides/mathparagraph/
---
**Herança:**  
java.lang.Object

**Todas as interfaces implementadas:**  
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject  
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

Parágrafo matemático que é um contêiner para blocos matemáticos (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | Inicializa uma nova instância da classe MathParagraph. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | Inicializa uma nova instância da classe MathParagraph. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getJustification()](#getJustification--) | Justificação do Parágrafo Valor padrão: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Justificação do Parágrafo Valor padrão: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Retorna o objeto Parent_Immediate. |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o item no índice especificado. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Obtém o item no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | Adiciona IMathBlock ao final da coleção. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | Determina se a coleção contém um valor específico. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | Determina o índice de um IMathBlock específico na coleção. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | Insere IMathBlock na coleção no índice especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove um item no índice especificado da coleção. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Salva o conteúdo deste [MathParagraph](../../com.aspose.slides/mathparagraph) como MathML |
| [toLatex()](#toLatex--) | Obtém a equação matemática no formato LaTeX |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

Inicializa uma nova instância da classe MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
> ```

### MathParagraph(IMathBlock mathBlock) {#MathParagraph-com.aspose.slides.IMathBlock-}
```
public MathParagraph(IMathBlock mathBlock)
```

Inicializa uma nova instância da classe MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

Justificação do Parágrafo Valor padrão: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Retorna:**  
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

Justificação do Parágrafo Valor padrão: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**  
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Retorna:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

Obtém o item no índice especificado. Somente leitura [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do item a ser obtido |

**Retorna:**  
[IMathBlock](../../com.aspose.slides/imathblock) - O bloco de um texto matemático.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

Obtém o item no índice especificado. Somente leitura [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do item a ser obtido |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | O bloco de um texto matemático. |

### clear() {#clear--}
```
public final void clear()
```

Remove todos os elementos da coleção.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
> ```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```

Adiciona IMathBlock ao final da coleção.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Um bloco matemático que será adicionado ao final da coleção |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

Remove a primeira ocorrência de um objeto específico da coleção.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | O objeto a ser removido da coleção. |

**Retorna:**  
boolean - true if mathBlock was successfully removed from the collection; otherwise, false. This method also returns false if mathBlock is not found in the original collection.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

Determina se a coleção contém um valor específico.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | O objeto a localizar na coleção. |

**Retorna:**  
boolean - true if mathBlock is found in the collection; otherwise, false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

Determina o índice de um IMathBlock específico na coleção.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | O item a localizar na coleção. |

**Retorna:**  
int - The index of mathBlock if found in the collection; otherwise, -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

Insere IMMathBlock na coleção no índice especificado.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual um item deve ser inserido. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | O IMathBlock a inserir. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove um item no índice especificado da coleção.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do item a remover. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**Retorna:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**Retorna:**  
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Salva o conteúdo deste [MathParagraph](../../com.aspose.slides/mathparagraph) como MathML

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |
### toLatex() {#toLatex--}
```
public final String toLatex()
```

Obtém a equação matemática no formato LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Retorna:**  
java.lang.String