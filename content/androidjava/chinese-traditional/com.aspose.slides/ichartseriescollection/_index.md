---
title: IChartSeriesCollection
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示集合
type: docs
url: /zh-hant/com.aspose.slides/ichartseriescollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

表示 [IChartSeries](../../com.aspose.slides/ichartseries) 的集合
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [add(int type)](#add-int-) | 建立新的圖表系列並將其新增至集合。 |
| [insert(int index, int type)](#insert-int-int-) | 建立新的圖表系列並將其插入到集合中。 |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | 根據 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 建立新的圖表系列並將其新增至集合。 |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | 根據 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) 建立新的圖表系列並將其新增至集合。 |
| [add(String name, int type)](#add-java.lang.String-int-) | 根據值建立新的圖表系列並將其新增至集合。 |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 搜尋指定的 [IChartSeries](../../com.aspose.slides/ichartseries)，並返回整個集合中首次出現的零基索引 |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的元素 |
| [clear()](#clear--) | 從集合中移除所有元素（包括圖表樣式）。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```


取得指定索引處的元素。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 指定索引處的元素。
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```


建立新的圖表系列並將其新增至集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | 系列類型 |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新的圖表系列。
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```


建立新的圖表系列並將其插入到集合中。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 插入的索引 |
| type | int | 圖表類型 [ChartType](../../com.aspose.slides/charttype) |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新的圖表系列 [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


根據 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 建立新的圖表系列並將其新增至集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 包含系列名稱的儲存格。 |
| type | int | 設定系列類型的類型

--------------------

如果從相同儲存格建立的圖表系列已在集合中，則此方法不會添加任何內容，並返回其索引。 |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已新增的圖表系列或已在集合中的系列。
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


根據 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) 建立新的圖表系列並將其新增至集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | 包含系列名稱的儲存格集合。 |
| type | int | 設定系列類型的類型

--------------------

如果從相同儲存格建立的圖表系列已在集合中，則此方法不會添加任何內容，並返回其索引。 |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已新增的圖表系列或已在集合中的系列。
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```


根據值建立新的圖表系列並將其新增至集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 系列名稱。 |
| type | int | 設定系列類型的類型 |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已新增的圖表系列。
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```


搜尋指定的 [IChartSeries](../../com.aspose.slides/ichartseries)，並返回整個集合中首次出現的零基索引

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 圖表系列值。 |

**Returns:**
int - 若找到，則返回值在整個 CollectionBase 中首次出現的零基索引；若未找到，則返回 -1。
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```


移除指定的值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 該值。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除指定索引處的元素

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 索引 |

### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有元素（包括圖表樣式）。