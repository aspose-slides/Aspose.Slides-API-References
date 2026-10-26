---
title: DrawingGuidesCollection
second_title: Aspose.Slides for Java API Referenciája
description: A beállítható rajzvezetékek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/drawingguidescollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

A beállítható rajzvezetékek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a rajzvezetőt az index alapján. |
| [add(byte orientation, float position)](#add-byte-float-) | Hozzáadja a rajzvezetőt a gyűjtemény végéhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a rajzvezetőt a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy felsoroló objektumot, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [getCount()](#getCount--) | Visszaadja az elemek számát a gyűjteményben. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Átmásolja az összes elemet a gyűjteményből a megadott tömbbe. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Visszaadja a rajzvezetőt az index alapján. Csak olvasható [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

Hozzáadja a rajzvezetőt a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| orientation | byte | Orientation of the drawing guide. |
| position | float | Position of the the drawing guide in points. |

**Visszatér:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a rajzvezetőt a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Index of the drawing guide that should be deleted. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes elemet a gyűjteményből.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Visszaad egy felsoroló objektumot, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - A IGenericEnumerator, amelyet a gyűjtemény bejárásához lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Egy java.util.Iterator a teljes gyűjteményhez.
### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja az elemek számát a gyűjteményben. Csak olvasható int.

**Visszatér:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Átmásolja az összes elemet a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |