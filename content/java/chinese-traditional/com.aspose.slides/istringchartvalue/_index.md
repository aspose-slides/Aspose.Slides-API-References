---
title: IStringChartValue
second_title: Aspose.Slides for Java API 參考
description: 表示可在 pptx 簡報文件中以兩種方式儲存的字串值：1) 與圖表相關之活頁簿的儲存格/多個儲存格；2) 文字常量值。
type: docs
url: /zh-hant/com.aspose.slides/istringchartvalue/
---
**所有已實作的介面：**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

表示可在 pptx 簡報文件中以兩種方式儲存的字串值：1) 位於與圖表相關之活頁簿的儲存格/多個儲存格中；2) 以文字常量形式。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | 如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則返回或設定文字常量字串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則返回或設定文字常量字串。 |
| [toString()](#toString--) | 返回字串表示形式。 |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 從指定的儲存格設定值。 |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | 如果 DataSourceType 屬性為 DataSourceType.Worksheet，則此方法返回活頁簿中代表字串資料之儲存格的位址。 |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則返回或設定文字常量字串。讀寫 String。

**傳回值：**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則返回或設定文字常量字串。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

返回字串表示形式。

**傳回值：**
java.lang.String - 字串值
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

從指定的儲存格設定值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 儲存格。 |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

如果 DataSourceType 屬性為 DataSourceType.Worksheet，則此方法返回活頁簿中代表字串資料之儲存格的位址。否則返回空字串。

**傳回值：**
java.lang.String - 字串值