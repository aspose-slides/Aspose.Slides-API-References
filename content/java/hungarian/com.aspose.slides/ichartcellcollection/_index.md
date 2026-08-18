---
title: IChartCellCollection
second_title: Aspose.Slides for Java API hivatkozás
description: Cellákat és adatokat tartalmazó gyűjteményt reprezentál.
type: docs
url: /hu/com.aspose.slides/ichartcellcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Cellákat és adatokat tartalmazó gyűjteményt reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | A munkafüzetben lévő cellakészlet címét adja vissza. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Az összes cella karakterlánc értékeiből álló összefűzött string. |
| [get_Item(int index)](#get-Item-int-) | Egy cellát (IChartDataCell) ad vissza index alapján. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Új cellát ad hozzá a gyűjteményhez. |
| [add(Object value)](#add-java.lang.Object-) | Létrehozza a [IChartDataCell](../../com.aspose.slides/ichartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy cellát a gyűjteményből index alapján. |
| [getCount()](#getCount--) | A gyűjteményben lévő cellák számát adja vissza. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


A munkafüzetben lévő cellakészlet címét adja vissza.

**Visszatérési érték:**
java.lang.String - A munkafüzetben lévő cellakészlet címe String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Az összes cella karakterlánc értékeiből álló összefűzött string.

**Visszatérési érték:**
java.lang.String - Eredmény string String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Egy cellát (IChartDataCell) ad vissza index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A cella indexe. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Adatot tartalmazó cella.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Új cellát ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az új cella, amelyet hozzá kell adni. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Létrehozza a [IChartDataCell](../../com.aspose.slides/ichartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object | Az érték.

--------------------
Ez a módszer hozzáad egy AUTO_DATA nevű munkalapot, és oda minden értéket beilleszti. Ha a [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)-t használja Cell értékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ezt a munkalapot ne használja. A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolít egy cellát a gyűjteményből index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A cella indexe, amelyet el kell távolítani. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


A gyűjteményben lévő cellák számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int