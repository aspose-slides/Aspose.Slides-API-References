---
title: ChartCellCollection
second_title: Aspose.Slides for Java API Referenciája
description: Adategységet tartalmazó cellák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/chartcellcollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Az adatot tartalmazó cellák gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Visszaadja a munkafüzetben lévő cellák készletének címét. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Összefűzött karakterlánc az összes cella szöveges értékéből. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy cellát (IChartDataCell) index alapján. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Új cellát ad a gyűjteményhez. |
| [add(Object value)](#add-java.lang.Object-) | Létrehozza a [ChartDataCell](../../com.aspose.slides/chartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy cellát a gyűjteményből index alapján. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben lévő cellák számát. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Visszaadja a munkafüzetben lévő cellák készletének címét.

**Visszatér:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Összefűzött karakterlánc az összes cella szöveges értékéből.

**Visszatér:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


Visszaad egy cellát (IChartDataCell) index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A cella indexe. |

**Visszatér:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Adataival rendelkező cella.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Új cellát ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az új hozzáadandó cella. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Létrehozza a [ChartDataCell](../../com.aspose.slides/chartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object | Az érték.

--------------------

Ez a metódus hozzáad egy AUTO_DATA nevű munkalapot, és oda minden értéket beilleszti. Ha a [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook)-t használja Cell értékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ne használja ezt a munkalapot. A metódus által hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy cellát a gyűjteményből index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó cella indexe. |

### getCount() {#getCount--}
```
public final int getCount()
```


Lekéri a gyűjteményben lévő cellák számát. Csak olvasható int.

**Visszatér:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárására lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Egy java.util.Iterator a teljes gyűjteményhez.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaad egy Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject