---
title: FillFormatCollection
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: A kitöltési stílusok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/fillformatcollection/
---
**Öröklődés:**
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**
[com.aspose.slides.IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
```
public final class FillFormatCollection extends DomObject<FormatScheme> implements IFillFormatCollection
```

A kitöltési stílusok gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterálja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [size()](#size--) | A gyűjteményben ténylegesen tárolt elemek számát adja vissza. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Az összes elemet átmásolja a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Paraméterek:**
| Paraméter | Type | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```

Visszaad egy felsorolót, amely végigiterálja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - A IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - Egy java.util.Iterator a teljes gyűjteményhez.
### size() {#size--}
```
public final int size()
```

A gyűjteményben ténylegesen tárolt elemek számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Az összes elemet átmásolja a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Type | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object