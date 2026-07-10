---
title: IChartCellCollection
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示包含数据的单元格集合。
type: docs
url: /zh/com.aspose.slides/ichartcellcollection/
---
**所有实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

表示包含数据的单元格集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 返回工作簿中单元格集合的地址。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 将所有单元格的字符串值连接成一个字符串。 |
| [get_Item(int index)](#get-Item-int-) | 根据索引返回一个单元格 (IChartDataCell)。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 向集合中添加新单元格。 |
| [add(Object value)](#add-java.lang.Object-) | 从指定值创建 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 并将其添加到集合中。 |
| [removeAt(int index)](#removeAt-int-) | 根据索引从集合中移除单元格。 |
| [getCount()](#getCount--) | 获取集合中单元格的数量。 |

### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

返回工作簿中单元格集合的地址。

**返回：**
java.lang.String - 工作簿中单元格集合的地址 String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

将所有单元格的字符串值连接成一个字符串。

**返回：**
java.lang.String - 结果字符串 String

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

根据索引返回一个单元格 (IChartDataCell)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 单元格的索引。 |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 包含数据的单元格。

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

向集合中添加新单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 要添加的新单元格。 |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

从指定值创建 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object | 该值。

--------------------

此方法会添加名为 AUTO_DATA 的工作表并在其中添加所有值。如果使用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) 来添加或编辑单元格值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

根据索引从集合中移除单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的单元格的索引。 |

### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合中单元格的数量。只读 int。

**返回：**
int