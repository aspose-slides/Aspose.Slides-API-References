---
title: ChartCellCollection
second_title: Aspose.Slides for Java API 参考
description: 表示包含数据的单元格集合。
type: docs
url: /zh/com.aspose.slides/chartcellcollection/
---
**继承：**
java.lang.Object

**实现的所有接口：**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

表示包含数据的单元格集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 返回工作簿中单元格集合的地址。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 从所有单元格的字符串值连接成的字符串。 |
| [get_Item(int index)](#get-Item-int-) | 根据索引返回一个单元格 (IChartDataCell)。 |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | 向集合中添加新单元格。 |
| [add(Object value)](#add-java.lang.Object-) | 从指定值创建 [ChartDataCell](../../com.aspose.slides/chartdatacell) 并将其添加到集合中。 |
| [removeAt(int index)](#removeAt-int-) | 根据索引从集合中移除一个单元格。 |
| [getCount()](#getCount--) | 获取集合中单元格的数量。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 Java 迭代器。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

返回工作簿中单元格集合的地址。

**返回：**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

从所有单元格的字符串值连接成的字符串。

**返回：**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

根据索引返回一个单元格 (IChartDataCell)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 单元格的索引。 |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 包含数据的单元格。
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

向集合中添加新单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 要添加的新单元格。 |
### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

从指定值创建 [ChartDataCell](../../com.aspose.slides/chartdatacell) 并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object | 该值。 |

--------------------

此方法会添加名为 AUTO_DATA 的工作表并在其中添加所有值。如果使用 [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) 添加或编辑单元格值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

根据索引从集合中移除一个单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的单元格索引。 |
### getCount() {#getCount--}
```
public final int getCount()
```

获取集合中单元格的数量。只读 int。

**返回：**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

返回整个集合的 Java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 整个集合的 java.util.Iterator。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject