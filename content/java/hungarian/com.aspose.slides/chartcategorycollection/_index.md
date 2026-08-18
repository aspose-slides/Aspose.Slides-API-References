---
title: ChartCategoryCollection
second_title: Aspose.Slides Java API referencia
description: A gyűjteményt képviseli
type: docs
url: /hu/com.aspose.slides/chartcategorycollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

[ChartCategory](../../com.aspose.slides/chartcategory) gyűjteményét képviseli
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Az adott indexű elemet adja vissza. |
| [getUseCells()](#getUseCells--) | Ha true, a munkalap a kategóriák tárolására lesz használva (ez az eset több szintű kategóriákat támogat). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Ha true, a munkalap a kategóriák tárolására lesz használva (ez az eset több szintű kategóriákat támogat). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Visszaadja a használt kategória csoportosítási szintek számát. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Ha a kategória létezik a gyűjteményben, visszaadja. |
| [add(Object value)](#add-java.lang.Object-) | Új [ChartCategory](../../com.aspose.slides/chartcategory)-t hoz létre az értékből, és hozzáadja a gyűjteményhez. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | A megadott [ChartCategory](../../com.aspose.slides/chartcategory)-t keresve visszaadja a nullától számláló első előfordulás indexét a teljes Collection-ben. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | A megadott értéket eltávolítja. |
| [removeAt(int index)](#removeAt-int-) | Az adott indexű elemet eltávolítja. |
| [clear()](#clear--) | A gyűjtemény összes elemét eltávolítja. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely a gyűjteményen iterál. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [size()](#size--) | Visszaadja a gyűjtemény elemeinek számát. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | A gyűjtemény összes elemét a megadott tömbbe másolja. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a Lista hozzáférése szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy objektumot, amely a gyűjteményhez való hozzáférés szinkronizálására használható. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Az adott indexű elemet adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - A megadott indexű elem.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Ha true, a munkalap a kategóriák tárolására lesz használva (ez az eset több szintű kategóriákat támogat). Ha false, a munkalap NEM lesz használva az értékek tárolására (és ez az eset nem támogat több szintű kategóriákat). Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Ha true, a munkalap a kategóriák tárolására lesz használva (ez az eset több szintű kategóriákat támogat). Ha false, a munkalap NEM lesz használva az értékek tárolására (és ez az eset nem támogat több szintű kategóriákat). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Visszaadja a használt kategória csoportosítási szintek számát. Több szintű kategóriáknál nagyobb, mint egy. Csak olvasható int.

**Visszatérési érték:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Ha a kategória létezik a gyűjteményben, visszaadja. Ellenkező esetben új diagramkategóriát hoz létre a(z) [IChartDataCell](../../com.aspose.slides/ichartdatacell) alapján, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell used to create chart category. |

**Visszatérési érték:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hozzáadott vagy már meglévő kategória.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Új [ChartCategory](../../com.aspose.slides/chartcategory)-t hoz létre az értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object | The value.

--------------------

Ez a metódus létrehozza az AUTO_DATA nevű munkalapot, és oda teszi az összes értéket. Ha [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook)-t használsz cellák hozzáadására vagy szerkesztésére, ügyelj arra, hogy ezt a munkalapot ne használd. A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.

**Visszatérési érték:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Added [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

A megadott [ChartCategory](../../com.aspose.slides/chartcategory)-t keresve visszaadja a nullától számláló első előfordulás indexét a teljes Collection-ben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Chart category. |

**Visszatérési érték:**
int - A nullától számláló első előfordulás indexe, ha megtalálható; egyébként -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

A megadott értéket eltávolítja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | The value. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Az adott indexű elemet eltávolítja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Index of a category to remove. |
### clear() {#clear--}
```
public final void clear()
```

A gyűjtemény összes elemét eltávolítja.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Visszaad egy enumerátort, amely a gyűjteményen iterál.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - A IGenericEnumerator, amely a gyűjteményen iterálhat.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjtemény elemeinek számát. Csak olvasható int.

**Visszatérési érték:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

A gyűjtemény összes elemét a megadott tömbbe másolja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a Lista hozzáférése szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy objektumot, amely a gyűjteményhez való hozzáférés szinkronizálására használható. Csak olvasható Object.

Visszaad egy szinkronizációs gyökért. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object