---
title: IChartCellCollection
second_title: Aspose.Slides Java API 参考
description: 表示包含数据的单元格集合。
type: docs
url: /zh/com.aspose.slides/ichartcellcollection/
---
**所有已实现的接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

表示包含数据的单元格集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 返回工作簿中单元格集合的地址。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 获取所有单元格字符串值的连接字符串。 |
| [get_Item(int index)](#get-Item-int-) | 按索引返回一个单元格 (IChartDataCell)。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 向集合中添加新单元格。 |
| [add(Object value)](#add-java.lang.Object-) | 根据指定的值创建 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 并将其添加到集合中。 |
| [removeAt(int index)](#removeAt-int-) | 按索引从集合中移除单元格。 |
| [getCount()](#getCount--) | 获取集合中单元格的数量。 |

### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

返回工作簿中单元格集合的地址。

**返回:**
java.lang.String - 工作簿中单元格集合的地址字符串

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

获取所有单元格字符串值的连接字符串。

**返回:**
java.lang.String - 结果字符串

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

按索引返回一个单元格 (IChartDataCell)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 单元格的索引。 |

**返回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 含数据的单元格。

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

向集合中添加新单元格。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 要添加的新单元格。 |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

根据指定的值创建 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 并将其添加到集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object | 值。 |

--------------------

此方法会添加名称为 AUTO_DATA 的工作表并将所有值添加到该工作表中。如果使用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) 来添加或编辑单元格值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

按索引从集合中移除单元格。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的单元格的索引。 |

### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合中单元格的数量。只读 int。

**返回:**
int