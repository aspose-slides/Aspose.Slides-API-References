---
title: IChartSeriesCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of
type: docs
weight: 699
url: /java/com.aspose.slides/ichartseriescollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Represents collection of [IChartSeries](../../com.aspose.slides/ichartseries)
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(int type)](#add-int-) | Creates new chart series and adds it to the collection. |
| [insert(int index, int type)](#insert-int-int-) | Creates new chart series and inserts it into the collection. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Creates new chart series from [IChartDataCell](../../com.aspose.slides/ichartdatacell) and adds it to the collection. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Creates new chart series from [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) and adds it to the collection. |
| [add(String name, int type)](#add-java.lang.String-int-) | Creates new chart series from value and adds it to the collection. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Searches for the specified [IChartSeries](../../com.aspose.slides/ichartseries) and returns the zero-based index of the first occurrence within the entire Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Removes the specified value. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index |
| [clear()](#clear--) | Removes all elements (including the chart style) from the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - The element at the specified index.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```


Creates new chart series and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of series |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - New chart series.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```


Creates new chart series and inserts it into the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index for insertion int |
| type | int | Chart type [ChartType](../../com.aspose.slides/charttype) |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - New chart series [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


Creates new chart series from [IChartDataCell](../../com.aspose.slides/ichartdatacell) and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell which contain series name. |
| type | int | Type set type of series

--------------------

If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series or series that already is in collection.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


Creates new chart series from [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Cells which contain series name. |
| type | int | Type set type of series

--------------------

If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series or series that already is in collection.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```


Creates new chart series from value and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Series name. |
| type | int | Type set type of series |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```


Searches for the specified [IChartSeries](../../com.aspose.slides/ichartseries) and returns the zero-based index of the first occurrence within the entire Collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Chart series value. |

**Returns:**
int - The zero-based index of the first occurrence of value within the entire CollectionBase, if found; otherwise, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index int |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements (including the chart style) from the collection.

