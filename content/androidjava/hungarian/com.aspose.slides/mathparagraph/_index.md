---
title: MathParagraph
second_title: Aspose.Slides Androidra - Java API referencia
description: Matematikai bekezdés, amely a matematikai blokkok (IMathBlock) tárolóját képezi
type: docs
url: /hu/com.aspose.slides/mathparagraph/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

Matematikai bekezdés, amely konténerként szolgál matematikai blokkok számára (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | Új példányt hoz létre a MathParagraph osztályból. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | Új példányt hoz létre a MathParagraph osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getJustification()](#getJustification--) | A bekezdés igazítása Alapértelmezett érték: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | A bekezdés igazítása Alapértelmezett érték: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | Visszaadja a Parent_Immediate objektumot. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben ténylegesen tárolt elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Lekéri a megadott indexű elemet. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | IMathBlock objektumot ad a gyűjtemény végéhez. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | Eltávolítja az adott objektum első előfordulását a gyűjteményből. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | Megállapítja egy adott IMathBlock indexét a gyűjteményben. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | Beszúr egy IMMathBlock objektumot a megadott indexre a gyűjteményben. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy elemet a megadott indexnél a gyűjteményből. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | A(z) [MathParagraph](../../com.aspose.slides/mathparagraph) tartalmát MathML formátumban menti |
| [toLatex()](#toLatex--) | Lekéri a matematikai egyenletet LaTeX formátumban |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

Új példányt hoz létre a MathParagraph osztályból.

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

Új példányt hoz létre a MathParagraph osztályból.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

A bekezdés igazítása Alapértelmezett érték: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Visszatérési érték:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

A bekezdés igazítása Alapértelmezett érték: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

Lekéri a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható int.

--------------------

> ```
> Példa:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

Lekéri a megadott indexű elemet. Csak olvasható [IMathBlock](../../com.aspose.slides/imathblock).

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A lekérdezendő elem nullával kezdődő indexe |
**Visszatérési érték:**
[IMathBlock](../../com.aspose.slides/imathblock) - A matematikai szöveg blokkja.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

Lekéri a megadott indexű elemet. Csak olvasható [IMathBlock](../../com.aspose.slides/imathblock).

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A lekérdezendő elem nullával kezdődő indexe |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | A matematikai szöveg blokkja. |
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja a gyűjtemény összes elemét.

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

IMathBlock objektumot ad a gyűjtemény végéhez.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Egy matematikai blokk, amely a gyűjtemény végéhez lesz hozzáadva |
### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

Eltávolítja az adott objektum első előfordulását a gyűjteményből.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | Az eltávolítandó objektum a gyűjteményből. |
**Visszatérési érték:**
boolean - igaz, ha a mathBlock sikeresen eltávolításra került a gyűjteményből; egyébként hamis. Ez a metódus hamis értéket ad vissza, ha a mathBlock nem található az eredeti gyűjteményben.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket.

--------------------

> ```
> Példa:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | A keresett objektum a gyűjteményben. |
**Visszatérési érték:**
boolean - igaz, ha a mathBlock megtalálható a gyűjteményben; egyébként hamis.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

Megállapítja egy adott IMathBlock indexét a gyűjteményben.

--------------------

> ```
> Példa:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | A keresett elem a gyűjteményben. |
**Visszatérési érték:**
int - A mathBlock indexe, ha megtalálható a gyűjteményben; egyébként -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

Beszúr egy IMathBlock objektumot a megadott indexre a gyűjteményben.

--------------------

> ```
> Példa:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullával kezdődő index, ahová az elemet be kell szúrni. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | A beszúrandó IMathBlock. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolít egy elemet a megadott indexnél a gyűjteményből.

--------------------

> ```
> Példa:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullával kezdődő index, amelynél az elem el lesz távolítva. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**Visszatérési érték:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

A(z) [MathParagraph](../../com.aspose.slides/mathparagraph) tartalmát MathML formátumban menti

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |
### toLatex() {#toLatex--}
```
public final String toLatex()
```

Lekéri a matematikai egyenletet LaTeX formátumban

--------------------

> ```
> Példa:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Visszatérési érték:**
java.lang.String