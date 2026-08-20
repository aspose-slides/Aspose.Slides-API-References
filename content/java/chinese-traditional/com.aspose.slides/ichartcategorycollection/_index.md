---
title: IChartCategoryCollection
second_title: Aspose.Slides Java API 參考
description: 表示集合
type: docs
url: /zh-hant/com.aspose.slides/ichartcategorycollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

表示 [IChartCategory](../../com.aspose.slides/ichartcategory) 的集合
## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUseCells()](#getUseCells--) | 若為 true，則工作表用於儲存類別（此情況支援多層類別）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | 若為 true，則工作表用於儲存類別（此情況支援多層類別）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 回傳使用的類別分組層級數量。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 若集合中存在該類別，回傳它。 |
| [add(Object value)](#add-java.lang.Object-) | 從值建立新的 [IChartCategory](../../com.aspose.slides/ichartcategory)，並將其加入集合。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 搜尋指定的 [IChartCategory](../../com.aspose.slides/ichartcategory)，並回傳在整個 Collection 中首次出現的零基索引 |
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

若為 true，則工作表用於儲存類別（此情況支援多層類別）。若為 false，則工作表不會用於儲存數值（此情況不支援多層類別）。讀寫布林。

**Returns:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

若為 true，則工作表用於儲存類別（此情況支援多層類別）。若為 false，則工作表不會用於儲存數值（此情況不支援多層類別）。讀寫布林。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

回傳使用的類別分組層級數量。若為多層類別，則會大於一。唯讀 int。

**Returns:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

若集合中已存在該類別，回傳它。否則從 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 建立新圖表類別並加入集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 用於建立圖表類別的儲存格。 |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已新增或已存在的類別。
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

從值建立新的 [IChartCategory](../../com.aspose.slides/ichartcategory)，並將其加入集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | 此值。

--------------------

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值寫入該工作表。若使用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) 來新增或編輯儲存格值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680 |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已新增 [IChartCategory](../../com.aspose.slides/ichartcategory)。
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

搜尋指定的 [IChartCategory](../../com.aspose.slides/ichartcategory)，並回傳在整個 Collection 中首次出現的零基索引

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 圖表類別。 |

**Returns:**
int - 若在整個 CollectionBase 中找到，則回傳該值首次出現的零基索引；否則回傳 -1。
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

移除指定的值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 此值。 |

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

移除集合中的所有元素。