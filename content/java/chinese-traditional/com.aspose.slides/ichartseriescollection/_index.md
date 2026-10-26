---
title: IChartSeriesCollection
second_title: Aspose.Slides for Java API 參考
description: 表示集合
type: docs
url: /zh-hant/com.aspose.slides/ichartseriescollection/
---
**所有已实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

表示 [IChartSeries](../../com.aspose.slides/ichartseries) 的集合
## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [add(int type)](#add-int-) | 建立新的圖表系列並將其加入集合。 |
| [insert(int index, int type)](#insert-int-int-) | 建立新的圖表系列並插入集合中。 |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | 從 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 建立新的圖表系列並加入集合。 |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | 從 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) 建立新的圖表系列並加入集合。 |
| [add(String name, int type)](#add-java.lang.String-int-) | 從值建立新的圖表系列並加入集合。 |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 搜尋指定的 [IChartSeries](../../com.aspose.slides/ichartseries)，並回傳整個集合中首次出現的零基索引。 |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的元素 |
| [clear()](#clear--) | 從集合中移除所有元素（包括圖表樣式）。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

取得指定索引處的元素。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 指定索引處的元素。
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

建立新的圖表系列並將其加入集合。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | 系列的類型 |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新的圖表系列。
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

建立新的圖表系列並插入集合中。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 插入的索引 |
| type | int | 圖表類型 [ChartType](../../com.aspose.slides/charttype) |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新的圖表系列 [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

從 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 建立新的圖表系列並加入集合。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 包含系列名稱的儲存格。 |
| type | int | 系列的類型

--------------------

如果圖表系列是從已在集合中的相同儲存格建立，則此方法不做任何添加，並返回其索引。 |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已加入的圖表系列或已在集合中的系列。
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

從 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) 建立新的圖表系列並加入集合。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | 包含系列名稱的儲存格集合。 |
| type | int | 系列的類型

--------------------

如果圖表系列是從已在集合中的相同儲存格建立，則此方法不做任何添加，並返回其索引。 |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已加入的圖表系列或已在集合中的系列。
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

從值建立新的圖表系列並加入集合。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 系列名稱。 |
| type | int | 系列的類型 |

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已加入的圖表系列。
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

搜尋指定的 [IChartSeries](../../com.aspose.slides/ichartseries)，並回傳整個集合中首次出現的零基索引。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 圖表系列的值。 |

**返回值：**
int - 如果找到，則返回值在整個 CollectionBase 中首次出現的零基索引；若未找到，則返回 -1。
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

移除指定的值。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 該值。 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引處的元素

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 索引。 |
### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有元素（包括圖表樣式）。