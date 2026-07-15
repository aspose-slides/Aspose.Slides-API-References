---
title: ChartCellCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表一個包含資料的儲存格集合。
type: docs
url: /zh-hant/com.aspose.slides/chartcellcollection/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

代表一個包含資料的儲存格集合。
## Methods

| Method | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 傳回工作簿中儲存格集合的位址。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 從所有儲存格字串值串接而成的字串。 |
| [get_Item(int index)](#get-Item-int-) | 依索引傳回儲存格 (IChartDataCell)。 |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | 將新儲存格加入集合。 |
| [add(Object value)](#add-java.lang.Object-) | 從指定的值建立 [ChartDataCell](../../com.aspose.slides/chartdatacell) 並加入集合。 |
| [removeAt(int index)](#removeAt-int-) | 依索引從集合中移除儲存格。 |
| [getCount()](#getCount--) | 取得集合中儲存格的數量。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```


傳回工作簿中儲存格集合的位址。

**返回:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```


從所有儲存格字串值串接而成的字串。

**返回:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```


依索引傳回儲存格 (IChartDataCell)。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 儲存格的索引。 |

**返回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 包含資料的儲存格。
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```


將新儲存格加入集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 要加入的新儲存格。 |
### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```


從指定的值建立 [ChartDataCell](../../com.aspose.slides/chartdatacell) 並加入集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | |
| value | java.lang.Object | 值。

--------------------

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值加入其中。如果您使用 [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) 來新增或編輯 Cell 值，請確保不要使用此工作表。使用此方法新增的值之最大數量不得超過 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


依索引從集合中移除儲存格。

**參數:**
| Parameter | Type | Description |
| --- | --- | |
| index | int | 要移除的儲存格索引。 |
### getCount() {#getCount--}
```
public final int getCount()
```


取得集合中儲存格的數量。唯讀 int。

**返回:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```


傳回可遍歷集合的列舉器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```


傳回整個集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - 整個集合的 java.util.Iterator。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject