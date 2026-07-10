---
title: ChartCellCollection
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示包含数据的单元格集合。
type: docs
url: /zh/com.aspose.slides/chartcellcollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject  
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

表示包含数据的单元格集合。

## Methods

| Method | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 返回工作簿中单元格集合的地址。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 将所有单元格的字符串值连接成一个字符串。 |
| [get_Item(int index)](#get-Item-int-) | 按索引返回一个单元格 (IChartDataCell)。 |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | 向集合中添加新单元格。 |
| [add(Object value)](#add-java.lang.Object-) | 从指定值创建 [ChartDataCell](../../com.aspose.slides/chartdatacell) 并将其添加到集合中。 |
| [removeAt(int index)](#removeAt-int-) | 按索引从集合中移除单元格。 |
| [getCount()](#getCount--) | 获取集合中单元格的数量。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

返回工作簿中单元格集合的地址。

**Returns:**  
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

将所有单元格的字符串值连接成一个字符串。

**Returns:**  
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

按索引返回一个单元格 (IChartDataCell)。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 单元格的索引。 |

**Returns:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 包含数据的单元格。

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

向集合中添加新单元格。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 要添加的新单元格。 |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

从指定值创建 [ChartDataCell](../../com.aspose.slides/chartdatacell) 并将其添加到集合中。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | 该值。

--------------------

此方法会添加名为 AUTO_DATA 的工作表并将所有值写入其中。如果使用 [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) 添加或编辑单元格值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

按索引从集合中移除单元格。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除的单元格索引。 |

### getCount() {#getCount--}
```
public final int getCount()
```

获取集合中单元格的数量。只读 int。

**Returns:**  
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

返回遍历集合的枚举器。

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

返回整个集合的 java 迭代器。

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 一个 java.util.Iterator，适用于整个集合。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**Returns:**  
com.aspose.slides.IDOMObject