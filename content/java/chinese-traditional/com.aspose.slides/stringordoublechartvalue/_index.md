---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for Java API 參考
description: 表示可以兩種方式儲存在 pptx 簡報文件中的字串或 double 值：1）與圖表相關的工作簿儲存格/儲存格；2）作為字面值。
type: docs
url: /zh-hant/com.aspose.slides/stringordoublechartvalue/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**所有已實作的介面:**  
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

表示可以以兩種方式儲存在 pptx 簡報文件中的字串或 double 值：1）工作簿中與圖表相關的儲存格；2）作為字面值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getAsCell()](#getAsCell--) | 取得或設定圖表資料儲存格。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 取得或設定圖表資料儲存格。 |
| [getAsLiteralString()](#getAsLiteralString--) | 取得或設定值為字面字串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 取得或設定值為字面字串。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 取得或設定值為字面 double。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 取得或設定值為字面 double。 |
| [getData()](#getData--) | 取得或設定 Data 物件。 |
| [setData(Object value)](#setData-java.lang.Object-) | 取得或設定 Data 物件。 |
| [toDouble()](#toDouble--) | 轉換為 double。 |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

取得或設定圖表資料儲存格。 讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**返回:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

取得或設定圖表資料儲存格。 讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

取得或設定值為字面字串。 讀寫 String。

**返回:**  
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

取得或設定值為字面字串。 讀寫 String。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

取得或設定值為字面 double。 讀寫 double。

**返回:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

取得或設定值為字面 double。 讀寫 double。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

取得或設定 Data 物件。 讀寫 Object。

**返回:**  
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

取得或設定 Data 物件。 讀寫 Object。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

轉換為 double。

**返回:**  
double - 雙精度值。