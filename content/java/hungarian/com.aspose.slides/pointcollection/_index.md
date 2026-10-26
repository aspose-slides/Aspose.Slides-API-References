---
title: PointCollection
second_title: Aspose.Slides Java API Referenciája
description: Az animációs pontok gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/pointcollection/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Az animációs pontok gyűjteményét reprezentálja.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Visszatér a gyűjteményben lévő pontok számával. |
| [get_Item(int index)](#get-Item-int-) | Visszatér egy ponttal a megadott indexen. |
| [iterator()](#iterator--) | Visszatér egy enumerátorral, amely a gyűjteményen iterál. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral a teljes gyűjteményhez. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```

Visszatér a gyűjteményben lévő pontok számával. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

Visszatér egy ponttal a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatér:**
[IPoint](../../com.aspose.slides/ipoint) - A [IPoint](../../com.aspose.slides/ipoint) objektum.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

Visszatér egy enumerátorral, amely a gyűjteményen iterál.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Egy java.util.Iterator a teljes gyűjteményhez.