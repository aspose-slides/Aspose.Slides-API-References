---
title: DrawingGuidesCollection
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy állítható rajzvezetékek gyűjteményét képviseli.
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

Egy állítható rajzvezetékek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a rajzvezetékét az index alapján. |
| [add(byte orientation, float position)](#add-byte-float-) | Hozzáadja a rajzvezetékét a gyűjtemény végéhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a rajzvezetékét a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [getCount()](#getCount--) | Visszaadja a gyűjteményben lévő elemek számát. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Visszaadja a rajzvezetékét az index alapján. Csak olvasható [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

Hozzáadja a rajzvezetékét a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| orientation | byte | A rajzvezeték orientációja. |
| position | float | A rajzvezeték pozíciója pontokban. |

**Visszatérési érték:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a rajzvezetékét a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó rajzvezeték indexe. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja a gyűjtemény összes elemét.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja a gyűjteményben lévő elemek számát. Csak olvasható int.

**Visszatérési érték:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |