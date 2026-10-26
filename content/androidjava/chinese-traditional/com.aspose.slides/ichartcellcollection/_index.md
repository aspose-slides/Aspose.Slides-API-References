---
title: IChartCellCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示包含資料的儲存格集合。
type: docs
url: /zh-hant/com.aspose.slides/ichartcellcollection/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

表示包含資料的儲存格集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | 返回工作簿中儲存格集合的位址。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | 將所有儲存格的字串值串接成字串。 |
| [get_Item(int index)](#get-Item-int-) | 依索引返回儲存格 (IChartDataCell)。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 將新儲存格新增至集合。 |
| [add(Object value)](#add-java.lang.Object-) | 從指定值建立 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 並將其加入集合。 |
| [removeAt(int index)](#removeAt-int-) | 依索引從集合中移除儲存格。 |
| [getCount()](#getCount--) | 取得集合中儲存格的計數。 |

### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

返回工作簿中儲存格集合的位址。

**傳回值:**
java.lang.String - 工作簿中儲存格集合的位址 String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

將所有儲存格的字串值串接成字串。

**傳回值:**
java.lang.String - 結果字串 String

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

依索引返回儲存格 (IChartDataCell)。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | int | 儲存格的索引。 |

**傳回值:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 含資料的儲存格。

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

將新儲存格新增至集合。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 要新增的儲存格。 |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

從指定值建立 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 並將其加入集合。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | java.lang.Object | 值。 |

--------------------

此方法會新增名為 AUTO\_DATA 的工作表並將所有值寫入其中。若使用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) 來新增或編輯儲存格值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

依索引從集合中移除儲存格。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | int | 要移除的儲存格之索引。 |

### getCount() {#getCount--}
```
public abstract int getCount()
```

取得集合中儲存格的計數。唯讀 int。

**傳回值:**
int