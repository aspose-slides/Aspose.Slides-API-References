---
title: MathParagraph
second_title: Aspose.Slides dla Java – dokumentacja API
description: Matematyczny akapit, który jest kontenerem dla bloków matematycznych IMathBlock
type: docs
url: /pl/com.aspose.slides/mathparagraph/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

Matematyczny akapit, który jest kontenerem dla bloków matematycznych (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | Inicjalizuje nową instancję klasy MathParagraph. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | Inicjalizuje nową instancję klasy MathParagraph. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Domyślna wartość: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Domyślna wartość: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Zwraca obiekt Parent_Immediate. |
| [getCount()](#getCount--) | Zwraca liczbę elementów faktycznie zawartych w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element o określonym indeksie. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Zwraca element o określonym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | Dodaje IMathBlock na koniec kolekcji. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | Określa, czy kolekcja zawiera określoną wartość. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | Określa indeks określonego IMathBlock w kolekcji. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | Wstawia IMathBlock do kolekcji pod wskazanym indeksem. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o określonym indeksie w kolekcji. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Zapisuje zawartość tego [MathParagraph](../../com.aspose.slides/mathparagraph) jako MathML |
| [toLatex()](#toLatex--) | Pobiera równanie matematyczne w formacie LaTeX |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```


Inicjalizuje nową instancję klasy MathParagraph.

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


Inicjalizuje nową instancję klasy MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```


Paragraph Justification Domyślna wartość: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Zwraca:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```


Paragraph Justification Domyślna wartość: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```


Zwraca liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```


Zwraca element o określonym indeksie. Tylko do odczytu [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Przykład:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze elementu do pobrania |

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - Blok tekstu matematycznego.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```


Zwraca element o określonym indeksie. Tylko do odczytu [IMathBlock](../../com.aspose.slides/imathblock).

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze elementu do pobrania |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Blok tekstu matematycznego. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie elementy z kolekcji.

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


Dodaje IMathBlock na koniec kolekcji.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Matematyczny blok, który zostanie dodany na koniec kolekcji |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```


Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

--------------------

> ```
> Przykład:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Obiekt do usunięcia z kolekcji. |

**Zwraca:**
boolean - true jeśli mathBlock został pomyślnie usunięty z kolekcji; w przeciwnym razie false. Metoda zwraca również false, jeśli mathBlock nie został znaleziony w oryginalnej kolekcji.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```


Określa, czy kolekcja zawiera określoną wartość.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Obiekt do zlokalizowania w kolekcji. |

**Zwraca:**
boolean - true jeśli mathBlock został znaleziony w kolekcji; w przeciwnym razie false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```


Określa indeks określonego IMMathBlock w kolekcji.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Element do zlokalizowania w kolekcji. |

**Zwraca:**
int - Indeks mathBlock, jeśli został znaleziony w kolekcji; w przeciwnym razie -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```


Wstawia IMathBlock do kolekcji pod wskazanym indeksem.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym ma zostać wstawiony element. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock do wstawienia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa element pod wskazanym indeksem w kolekcji.

--------------------

> ```
> Przykład:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze elementu do usunięcia. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```




**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```




**Zwraca:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


Zapisuje zawartość tego [MathParagraph](../../com.aspose.slides/mathparagraph) jako MathML

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |

### toLatex() {#toLatex--}
```
public final String toLatex()
```


Pobiera równanie matematyczne w formacie LaTeX

--------------------

> ```
> Przykład:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Zwraca:**
java.lang.String