---
title: StringChartValue
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表可在 pptx 簡報文件中以兩種方式儲存的字串值：1) 圖表相關工作簿的儲存格/儲存格群組；2) 作為文字值。
type: docs
url: /zh-hant/com.aspose.slides/stringchartvalue/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**所有已實作的介面：**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

表示可在 pptx 簡報文件中以兩種方式儲存的字串值：1）圖表相關工作簿的儲存格/儲存格群組中；2）作為文字值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsCells()](#getAsCells--) | 不允許指派空值。 |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | 不允許指派空值。 |
| [getAsLiteralString()](#getAsLiteralString--) | 取得或設定值為文字字串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 取得或設定值為文字字串。 |
| [getData()](#getData--) | 取得或設定 Data 物件。 |
| [setData(Object value)](#setData-java.lang.Object-) | 取得或設定 Data 物件。 |
| [toString()](#toString--) | 取得字串值資料。 |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 從指定的儲存格設定值。 |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | 如果 DataSourceType 屬性為 DataSourceType.Worksheet，則此方法會回傳工作簿中代表字串資料之儲存格位址。 |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

不允許指派空值。回傳值永遠不為空。讀寫 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)。

**回傳：**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

不允許指派空值。回傳值永遠不為空。讀寫 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

取得或設定值為文字字串。讀寫 String。

**回傳：**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

取得或設定值為文字字串。讀寫 String。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

取得或設定 Data 物件。讀寫 Object。

**回傳：**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

取得或設定 Data 物件。讀寫 Object。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

取得字串值資料。如果 DataSourceType 為 false 且未指派字串值，則回傳 null。

**回傳：**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

從指定的儲存格設定值。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 儲存格。 |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

如果 DataSourceType 屬性為 DataSourceType.Worksheet，則此方法回傳工作簿中代表字串資料之儲存格位址。否則回傳空字串。

**回傳：**
java.lang.String