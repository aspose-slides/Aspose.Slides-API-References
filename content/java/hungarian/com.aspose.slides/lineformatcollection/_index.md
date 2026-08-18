---
title: LineFormatCollection
second_title: Aspose.Slides for Java API Referenciája
description: A vonalstílusok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/lineformatcollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

A vonalstílusok gyűjteményét képviseli.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [size()](#size--) | A gyűjteményben ténylegesen tárolt elemek számát adja meg. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Az összes elemet átmásolja a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely azt jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```


A megadott indexű elemet adja vissza. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat} - A IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat} - Egy java.util.Iterator a teljes gyűjteményhez.
### size() {#size--}
```
public final int size()
```


A gyűjteményben ténylegesen tárolt elemek számát adja meg. Csak olvasható int.

**Visszatérési érték:**
int
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

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely azt jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object