---
title: ChartCellCollection
second_title: Aspose.Slides for Java API 參考
description: 表示包含資料的儲存格集合。
type: docs
url: /zh-hant/com.aspose.slides/chartcellcollection/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

表示包含資料的儲存格集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 返回工作簿中儲存格集合的地址。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 將所有儲存格的字串值串接為一個字串。 |
| [get_Item(int index)](#get-Item-int-) | 根據索引返回一個儲存格 (IChartDataCell)。 |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | 將新儲存格加入集合。 |
| [add(Object value)](#add-java.lang.Object-) | 從指定的值建立 [ChartDataCell](../../com.aspose.slides/chartdatacell) 並將其加入集合。 |
| [removeAt(int index)](#removeAt-int-) | 依索引從集合中移除儲存格。 |
| [getCount()](#getCount--) | 取得集合中儲存格的數量。 |
| [iterator()](#iterator--) | 返回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


返回工作簿中儲存格集合的地址。

**返回：**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


將所有儲存格的字串值串接為一個字串。

**返回：**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


根據索引返回一個儲存格 (IChartDataCell)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 儲存格的索引。 |

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 含資料的儲存格。
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


將新儲存格加入集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 要新增的儲存格。 |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


從指定的值建立 [ChartDataCell](../../com.aspose.slides/chartdatacell) 並將其加入集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object | 值。

--------------------

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值寫入其中。若使用 [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) 來新增或編輯儲存格的值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


依索引從集合中移除儲存格。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的儲存格的索引。 |

### getCount() {#getCount--}
```
public final int getCount()
```


取得集合中儲存格的數量。唯讀 int。

**返回：**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


返回一個可遍歷集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


返回整個集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 整個集合的 java.util.Iterator。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject