---
title: ChartCategoryCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Gyűjteményt képvisel
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

A [ChartCategory](../../com.aspose.slides/chartcategory) gyűjteményt képviseli
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [getUseCells()](#getUseCells--) | Ha igaz, akkor a munkalapot a kategóriák tárolására használják (ez az eset több szintű kategóriákat támogat). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Ha igaz, akkor a munkalapot a kategóriák tárolására használják (ez az eset több szintű kategóriákat támogat). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Visszaadja a használt kategória csoportosítási szintek számát. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Ha a kategória létezik a gyűjteményben, visszaadja. |
| [add(Object value)](#add-java.lang.Object-) | Létrehoz egy új [ChartCategory](../../com.aspose.slides/chartcategory) értékből, és hozzáadja a gyűjteményhez. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Keres a megadott [ChartCategory](../../com.aspose.slides/chartcategory)-ért, és visszaadja a nulláról induló indexet az első előfordulásra a teljes Collection-ben. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű elemet. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [size()](#size--) | Visszaadja a gyűjtemény elemeinek számát. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a List hozzáférése szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy objektumot, amelyet a gyűjtemény hozzáférésének szinkronizálásához lehet használni. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Visszaadja a megadott indexű elemet.

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

Ha igaz, akkor a munkalapot a kategóriák tárolására használják (ez az eset több szintű kategóriákat támogat). Ha hamis, akkor a munkalap NEM használható az értékek tárolására (és ez az eset nem támogat több szintű kategóriákat). Olvasható/írható boolean.

**Visszatérési érték:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Ha igaz, akkor a munkalapot a kategóriák tárolására használják (ez az eset több szintű kategóriákat támogat). Ha hamis, akkor a munkalap NEM használható az értékek tárolására (és ez az eset nem támogat több szintű kategóriákat). Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Visszaadja a használt kategória csoportosítási szintek számát. Több mint egy, ha több szintű kategóriákról van szó. Csak olvasható int.

**Visszatérési érték:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Ha a kategória létezik a gyűjteményben, visszaadja. Egyébként létrehoz egy új diagramkategóriát a [IChartDataCell](../../com.aspose.slides/ichartdatacell)-ból, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | A cella, amelyet a diagramkategória létrehozásához használnak. |

**Visszatérési érték:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hozzáadott vagy létező kategória.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Létrehoz egy új [ChartCategory](../../com.aspose.slides/chartcategory) értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object | Az érték.

--------------------

Ez a metódus hozzáad egy AUTO_DATA nevű munkalapot, és oda teszi az összes értéket. Ha a [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook)-t használja cellaértékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ezt a munkalapot ne használja. A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.

**Visszatérési érték:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hozzáadott [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Keres a megadott [ChartCategory](../../com.aspose.slides/chartcategory)-ért, és visszaadja a nulláról induló indexét az első előfordulásra a teljes Collection-ben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Chart category. |

**Visszatérési érték:**
int - A nulláról induló index az első előfordulásra a teljes CollectionBase-ben, ha megtalálható; egyébként -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | A value. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő kategória indexe. |
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja a gyűjtemény összes elemét.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - A IGenericEnumerator, amelyet a gyűjtemény bejárásához lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Egy java.util.Iterator a teljes gyűjteményhez.
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

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a tömbben. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a List hozzáférése szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy objektumot, amelyet a gyűjtemény hozzáférésének szinkronizálásához lehet használni. Csak olvasható Object.

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object