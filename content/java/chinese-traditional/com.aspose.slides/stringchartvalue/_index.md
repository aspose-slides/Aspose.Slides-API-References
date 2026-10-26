---
title: StringChartValue
second_title: Aspose.Slides for Java API 參考
description: 在 pptx 簡報文件中，以兩種方式儲存的字串值：1) 在與圖表相關的工作簿的儲存格/儲存格中；2) 作為文字值。
type: docs
url: /zh-hant/com.aspose.slides/stringchartvalue/
---
**繼承:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**全部已實作的介面:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

表示可在 pptx 簡報文件中以兩種方式儲存的字串值：1) 在與圖表相關聯的工作簿的儲存格/儲存格中；2) 作為文字值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getAsCells()](#getAsCells--) | 不允許指派 null 值。 |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | 不允許指派 null 值。 |
| [getAsLiteralString()](#getAsLiteralString--) | 返回或設定值為文字字串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 返回或設定值為文字字串。 |
| [getData()](#getData--) | 返回或設定 Data 物件。 |
| [setData(Object value)](#setData-java.lang.Object-) | 返回或設定 Data 物件。 |
| [toString()](#toString--) | 返回字串值資料。 |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 從指定的儲存格設定值。 |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | 如果 DataSourceType 屬性為 DataSourceType.Worksheet，則此方法返回工作簿中代表字串資料的儲存格地址。 |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

不允許指派 null 值。返回值始終不為 null。讀寫 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)。

**返回:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

不允許指派 null 值。返回值始終不為 null。讀寫 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

返回或設定值為文字字串。讀寫 String。

**返回:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

返回或設定值為文字字串。讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

返回或設定 Data 物件。讀寫 Object。

**返回:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

返回或設定 Data 物件。讀寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

返回字串值資料。如果 DataSourceType 為 false 且未指派字串值，則返回 null。

**返回:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

從指定的儲存格設定值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

如果 DataSourceType 屬性為 DataSourceType.Worksheet，則此方法返回工作簿中代表字串資料的儲存格地址。否則返回空字串。

**返回:**
java.lang.String