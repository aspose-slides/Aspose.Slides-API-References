---
title: IChartCategoryCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示集合
type: docs
url: /zh-hant/com.aspose.slides/ichartcategorycollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

表示 [IChartCategory](../../com.aspose.slides/ichartcategory) 的集合
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUseCells()](#getUseCells--) | 為 true 時，工作表用於存放類別（此情況支援多層類別）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | 為 true 時，工作表用於存放類別（此情況支援多層類別）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 傳回使用的類別分組層級數量。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 若集合中存在該類別，傳回它。 |
| [add(Object value)](#add-java.lang.Object-) | 從值建立新 [IChartCategory](../../com.aspose.slides/ichartcategory) 並加入集合。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 在整個 Collection 中搜尋指定的 [IChartCategory](../../com.aspose.slides/ichartcategory)，並傳回首次出現的零基索引 |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除給定索引處的元素。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```


取得指定索引處的元素。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 指定索引處的元素。
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```


為 true 時，工作表用於存放類別（此情況支援多層類別）。為 false 時，工作表不用於存放值（此情況不支援多層類別）。可讀寫布林值。

**Returns:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```


為 true 時，工作表用於存放類別（此情況支援多層類別）。為 false 時，工作表不用於存放值（此情況不支援多層類別）。可讀寫布林值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```


傳回使用的類別分組層級數量。對於多層類別而言，會大於一。唯讀 int。

**Returns:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```


若集合中已存在該類別，傳回它。否則從 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 建立新的圖表類別並加入集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 用於建立圖表類別的 Cell。 |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已加入或已存在的類別。
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```


從值建立新 [IChartCategory](../../com.aspose.slides/ichartcategory) 並加入集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | 該值。

--------------------

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值添加到該工作表。如果您使用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) 來新增或編輯儲存格值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680。

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已加入的 [IChartCategory](../../com.aspose.slides/ichartcategory)。
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```


搜尋指定的 [IChartCategory](../../com.aspose.slides/ichartcategory)，並傳回整個 Collection 中首次出現的零基索引

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 圖表類別。 |

**Returns:**
int - 若在整個 CollectionBase 中找到值，則傳回其零基索引；否則傳回 -1。
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```


移除指定的值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 該值。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除給定索引處的元素。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除之類別的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有元素。