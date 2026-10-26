---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for Android 透過 Java API 參考文件
description: 表示可儲存在 pptx 簡報文件中的字串或 double 值，有兩種方式：1) 在與圖表相關的工作簿的儲存格/儲存格中；2) 作為文字值。
type: docs
url: /zh-hant/com.aspose.slides/stringordoublechartvalue/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**所有已實作的介面：**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

表示可儲存在 pptx 簡報文件中的字串或 double 值，有兩種方式：1) 在與圖表相關的工作簿的儲存格/儲存格中；2) 作為文字值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsCell()](#getAsCell--) | 返回或設定圖表資料儲存格。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 返回或設定圖表資料儲存格。 |
| [getAsLiteralString()](#getAsLiteralString--) | 返回或設定值為文字字串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 返回或設定值為文字字串。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 返回或設定值為文字 double。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 返回或設定值為文字 double。 |
| [getData()](#getData--) | 返回或設定 Data 物件。 |
| [setData(Object value)](#setData-java.lang.Object-) | 返回或設定 Data 物件。 |
| [toDouble()](#toDouble--) | 轉換為 double。 |

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

返回或設定圖表資料儲存格。讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

返回或設定圖表資料儲存格。讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

返回或設定值為文字字串。讀寫 String。

**返回：**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

返回或設定值為文字字串。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

返回或設定值為文字 double。讀寫 double。

**返回：**
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

返回或設定值為文字 double。讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

返回或設定 Data 物件。讀寫 Object。

**返回：**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

返回或設定 Data 物件。讀寫 Object。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

轉換為 double。

**返回：**
double - Double 值。