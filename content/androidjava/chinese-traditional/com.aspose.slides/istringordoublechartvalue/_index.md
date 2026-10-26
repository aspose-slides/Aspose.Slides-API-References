---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示可以以兩種方式儲存在 pptx 簡報文件中的字串或 double 值：1）儲存在圖表相關工作簿的儲存格中；2）作為文字常值。
type: docs
url: /zh-hant/com.aspose.slides/istringordoublechartvalue/
---
**已實作介面:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

表示可以以兩種方式儲存在 pptx 簡報文件中的字串或 double 值：1）儲存在圖表相關工作簿的儲存格中；2）作為文字常值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | 如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則傳回或設定文字字面值。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則傳回或設定文字字面值。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 如果 DataSourceType 屬性為 DataSourceType.DoubleLiterals，則傳回或設定 double 字面值。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 如果 DataSourceType 屬性為 DataSourceType.DoubleLiterals，則傳回或設定 double 字面值。 |
| [toDouble()](#toDouble--) | 將值轉換為 double。 |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則傳回或設定文字字面值。讀寫 String。

**傳回:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則傳回或設定文字字面值。讀寫 String。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

如果 DataSourceType 屬性為 DataSourceType.DoubleLiterals，則傳回或設定 double 字面值。讀寫 double。

**傳回:**  
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

如果 DataSourceType 屬性為 DataSourceType.DoubleLiterals，則傳回或設定 double 字面值。讀寫 double。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

將值轉換為 double。

**傳回:**  
double - Double 值 double