---
title: IChartCellCollection
second_title: Aspose.Slides for Android Java API-referencia
description: Adataival rendelkező cellák gyűjteményét ábrázolja.
type: docs
url: /hu/com.aspose.slides/ichartcellcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

A cellákat tartalmazó gyűjteményt ábrázolja adatokkal.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Returns address of the set of cells in workbook. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Concatenation string from all cells string values. |
| [get_Item(int index)](#get-Item-int-) | Returns a cell (IChartDataCell) by index. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Add new cell to the collection. |
| [add(Object value)](#add-java.lang.Object-) | Creates [IChartDataCell](../../com.aspose.slides/ichartdatacell) from specified value and adds it to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a cell from the collection by index. |
| [getCount()](#getCount--) | Gets the count of cells in collection. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

Visszaadja a munkafüzetben lévő cellák készletének címét.

**Visszatérési érték:**
java.lang.String - A munkafüzetben lévő cellák készletének címe String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

Összefűzött karakterlánc az összes cella karakterlánc értékéből.

**Visszatérési érték:**
java.lang.String - Eredmény karakterlánc String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

Visszaad egy cellát (IChartDataCell) az index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A cella indexe. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Adataival rendelkező cella.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

Új cellát ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az új cella, amelyet hozzá kell adni. |
### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

Létrehozza a(z) [IChartDataCell](../../com.aspose.slides/ichartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object | Az érték.

--------------------

Ez a metódus hozzáad egy munkalapot AUTO_DATA névvel, és oda helyezi az összes értéket. Ha a(z) [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)-t használja cellaértékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ne használja ezt a munkalapot. A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy cellát a gyűjteményből az index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó cella indexe. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lekéri a gyűjteményben lévő cellák számát. Csak olvasható int.

**Visszatérési érték:**
int