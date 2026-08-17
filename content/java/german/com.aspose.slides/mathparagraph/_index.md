---
title: MathParagraph
second_title: Aspose.Slides für Java API-Referenz
description: Mathematischer Absatz, der ein Container für mathematische Blöcke IMathBlock ist
type: docs
url: /de/com.aspose.slides/mathparagraph/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

Mathematischer Absatz, der ein Container für mathematische Blöcke ist (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | Initialisiert eine neue Instanz der MathParagraph-Klasse. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | Initialisiert eine neue Instanz der MathParagraph-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getJustification()](#getJustification--) | Absatzausrichtung Standardwert: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Absatzausrichtung Standardwert: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Gibt das Parent_Immediate-Objekt zurück. |
| [getCount()](#getCount--) | Ermittelt die tatsächlich in der Sammlung enthaltene Elementanzahl. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Gibt das Element am angegebenen Index zurück. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | Fügt IMathBlock am Ende der Sammlung hinzu. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | Bestimmt den Index eines bestimmten IMMathBlock in der Sammlung. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | Fügt IMMathBlock an dem angegebenen Index in die Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein Element am angegebenen Index der Sammlung. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Speichert den Inhalt dieses [MathParagraph](../../com.aspose.slides/mathparagraph) als MathML |
| [toLatex()](#toLatex--) | Ermittelt die mathematische Gleichung im LaTeX-Format |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```


Initialisiert eine neue Instanz der MathParagraph-Klasse.

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


Initialisiert eine neue Instanz der MathParagraph-Klasse.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```


Absatzausrichtung Standardwert: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Rückgabewert:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```


Absatzausrichtung Standardwert: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```


Ermittelt die tatsächlich in der Sammlung enthaltene Elementanzahl. Nur lesbar int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Rückgabewert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur lesbar [IMathBlock](../../com.aspose.slides/imathblock).

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des abzurufenden Elements |

**Rückgabewert:**
[IMathBlock](../../com.aspose.slides/imathblock) - Der Block eines mathematischen Textes.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```


Gibt das Element am angegebenen Index zurück. Nur lesbar [IMathBlock](../../com.aspose.slides/imathblock).

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des abzurufenden Elements |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Der Block eines mathematischen Textes. |

### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Elemente aus der Sammlung.

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


Fügt IMMathBlock am Ende der Sammlung hinzu.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Ein mathematischer Block, der am Ende der Sammlung hinzugefügt wird |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```


Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Das zu entfernende Objekt aus der Sammlung. |

**Rückgabewert:**
boolean - true, wenn mathBlock erfolgreich aus der Sammlung entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn mathBlock in der ursprünglichen Sammlung nicht gefunden wird.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```


Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Das zu lokalisierende Objekt in der Sammlung. |

**Rückgabewert:**
boolean - true, wenn mathBlock in der Sammlung gefunden wurde; andernfalls false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```


Bestimmt den Index eines bestimmten IMMathBlock in der Sammlung.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Das zu lokalisierende Element in der Sammlung. |

**Rückgabewert:**
int - Der Index von mathBlock, falls gefunden; andernfalls -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```


Fügt IMMathBlock an dem angegebenen Index in die Sammlung ein.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem ein Element eingefügt werden soll. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Der einzufügende IMMathBlock. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt ein Element am angegebenen Index der Sammlung.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```




**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```




**Rückgabewert:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


Speichert den Inhalt dieses [MathParagraph](../../com.aspose.slides/mathparagraph) als MathML

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |

### toLatex() {#toLatex--}
```
public final String toLatex()
```


Ermittelt die mathematische Gleichung im LaTeX-Format

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Rückgabewert:**
java.lang.String