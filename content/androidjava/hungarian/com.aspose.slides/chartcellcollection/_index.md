---
title: ChartCellCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás szerint
description: Adatot tartalmazó cellák gyűjteményét képviseli.
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

Adatot tartalmazó cellák gyűjteményét képviseli.
## Metódusok

| Method | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Visszaadja a munkafüzet cellakészletének címét. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Visszaadja az összes cella karakterlánc értékeinek összefűzött karakterláncát. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy cellát (IChartDataCell) index szerint. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Új cellát ad a gyűjteményhez. |
| [add(Object value)](#add-java.lang.Object-) | Létrehozza a(z) [ChartDataCell](../../com.aspose.slides/chartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy cellát a gyűjteményből index alapján. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben lévő cellák számát. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


Visszaadja a munkafüzet cellakészletének címét.

**Visszatérési érték:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


Visszaadja az összes cella karakterlánc értékeinek összefűzött karakterláncát.

**Visszatérési érték:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


Visszaad egy cellát (IChartDataCell) index szerint.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A cella indexe. |

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Adatokkal rendelkező cella.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


Új cellát ad a gyűjteményhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Az új cella, amelyet hozzáad. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


Létrehozza a(z) [ChartDataCell](../../com.aspose.slides/chartdatacell)-t a megadott értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Az érték.

--------------------

Ez a metódus hozzáad egy munkalapot az AUTO_DATA névvel, és oda helyezi az összes értéket. Ha a [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook)-t használja cellaértékek hozzáadására vagy módosítására, ügyeljen arra, hogy ne használja ezt a munkalapot. A metódus által hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy cellát a gyűjteményből index alapján.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az eltávolítandó cella indexe. |

### getCount() {#getCount--}
```
public final int getCount()
```


Lekéri a gyűjteményben lévő cellák számát. Csak olvasható int.

**Visszatérési érték:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Egy IGenericEnumerator, amely használható a gyűjtemény bejárására.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - Egy java.util.Iterator a teljes gyűjteményhez.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaad egy Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject