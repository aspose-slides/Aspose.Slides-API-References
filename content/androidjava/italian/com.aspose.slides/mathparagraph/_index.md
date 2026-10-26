---
title: MathParagraph
second_title: Aspose.Slides per Android via Riferimento API Java
description: Paragrafo matematico che è un contenitore per blocchi matematici IMathBlock
type: docs
url: /it/com.aspose.slides/mathparagraph/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

Paragrafo matematico che è un contenitore per blocchi matematici (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | Inizializza una nuova istanza della classe MathParagraph. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | Inizializza una nuova istanza della classe MathParagraph. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getJustification()](#getJustification--) | Giustificazione del paragrafo Valore predefinito: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Giustificazione del paragrafo Valore predefinito: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Restituisce l'oggetto Parent_Immediate. |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Ottiene l'elemento all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | Aggiunge IMathBlock alla fine della collezione. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | Determina se la collezione contiene un valore specifico. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | Determina l'indice di uno specifico IMathBlock nella collezione. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | Inserisce IMathBlock nella collezione all'indice specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un elemento all'indice specificato della collezione. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Salva il contenuto di questo [MathParagraph](../../com.aspose.slides/mathparagraph) come MathML |
| [toLatex()](#toLatex--) | Ottiene l'equazione matematica in formato LaTeX |

### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

Inizializza una nuova istanza della classe MathParagraph.

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

Inizializza una nuova istanza della classe MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

Giustificazione del paragrafo Valore predefinito: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Restituisce:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

Giustificazione del paragrafo Valore predefinito: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

Ottiene il numero di elementi effettivamente contenuti nella collezione. Solo lettura int.

--------------------

> ```
> Esempio:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

Ottiene l'elemento all'indice specificato. Solo lettura [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Esempio:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da ottenere |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - Il blocco di un testo matematico.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

Ottiene l'elemento all'indice specificato. Solo lettura [IMathBlock](../../com.aspose.slides/imathblock).

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da ottenere |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Il blocco di un testo matematico. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla collezione.

--------------------

> ```
> Esempio:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```

Aggiunge IMathBlock alla fine della collezione.

--------------------

> ```
> Esempio:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Un blocco matematico che sarà aggiunto alla fine della collezione |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

Rimuove la prima occorrenza di un oggetto specifico dalla collezione.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | L'oggetto da rimuovere dalla collezione. |

**Restituisce:**
boolean - true se mathBlock è stato rimosso correttamente dalla collezione; altrimenti, false. Questo metodo restituisce false anche se mathBlock non è presente nella collezione originale.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

Determina se la collezione contiene un valore specifico.

--------------------

> ```
> Esempio:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | L'oggetto da individuare nella collezione. |

**Restituisce:**
boolean - true se mathBlock è presente nella collezione; altrimenti, false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

Determina l'indice di uno specifico IMathBlock nella collezione.

--------------------

> ```
> Esempio:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | L'elemento da trovare nella collezione. |

**Restituisce:**
int - L'indice di mathBlock se trovato nella collezione; altrimenti, -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

Inserisce IMMathBlock nella collezione all'indice specificato.

--------------------

> ```
> Esempio:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale inserire un elemento. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | L'IMathBlock da inserire. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove un elemento all'indice specificato della collezione.

--------------------

> ```
> Esempio:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock}
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**Restituisce:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Salva il contenuto di questo [MathParagraph](../../com.aspose.slides/mathparagraph) come MathML

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |

### toLatex() {#toLatex--}
```
public final String toLatex()
```

Ottiene l'equazione matematica in formato LaTeX

--------------------

> ```
> Esempio:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Restituisce:**
java.lang.String