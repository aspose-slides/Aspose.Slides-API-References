---
title: SmartArtShapeCollection
second_title: Aspose.Slides Androidra a Java API hivatkozásán keresztül
description: A SmartArt alakzatok gyűjteményét képviseli
type: docs
url: /hu/com.aspose.slides/smartartshapecollection/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

A SmartArt alakzatok gyűjteményét képviseli
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

Visszaadja a megadott indexű elemet. Csak olvasható [SmartArtShape](../../com.aspose.slides/smartartshape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Alakzat indexe |

**Visszatér:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - A SmartArt alakzat
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Egy IGenericEnumerator, amely a gyűjteményen történő iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Egy java.util.Iterator a teljes gyűjteményhez.