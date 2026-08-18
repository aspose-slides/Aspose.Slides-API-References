---
title: SmartArtShapeCollection
second_title: Aspose.Slides Java API referencia
description: SmartArt alakzatok gyűjteményét képviseli
type: docs
url: /hu/com.aspose.slides/smartartshapecollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

Egy SmartArt alakzatok gyűjteményét képvisel
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Agyak ténylegesen a gyűjteményben lévő számát adja vissza. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [isSynchronized()](#isSynchronized--) | Visszatér egy értékkel, amely azt jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszatér egy szinkronizációs gyökérrel. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Az összes elemet átmásolja a gyűjteményből a megadott tömbbe. |
| [iterator()](#iterator--) | Visszatér egy enumerátorral, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral a teljes gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

Agyak ténylegesen a gyűjteményben lévő számát adja vissza. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [SmartArtShape](../../com.aspose.slides/smartartshape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az alakzat indexe |

**Visszatér:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - a SmartArt alakzat
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszatér egy értékkel, amely azt jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszatér egy szinkronizációs gyökérrel. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Az összes elemet átmásolja a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

Visszatér egy enumerátorral, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - egy java.util.Iterator a teljes gyűjteményhez.