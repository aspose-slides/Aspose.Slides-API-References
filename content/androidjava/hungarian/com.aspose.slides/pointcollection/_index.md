---
title: PointCollection
second_title: Aspose.Slides Androidhoz, Java API hivatkozás
description: Az animációs pontok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/pointcollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Az animációs pontok gyűjteményét képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszaadja a gyűjteményben lévő pontok számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy pontot a megadott indexen. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

Visszaadja a gyűjteményben lévő pontok számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

Visszaad egy pontot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatér:**
[IPoint](../../com.aspose.slides/ipoint) - The [IPoint](../../com.aspose.slides/ipoint) objektum.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

Visszaad egy felsorolót, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Egy java.util.Iterator a teljes gyűjteményhez.