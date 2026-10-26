---
title: DoubleChartValue
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示可在 pptx 簡報文件中以兩種方式儲存的 double 值：1）在與圖表相關的工作簿的儲存格/儲存格中；2）作為文字值。
type: docs
url: /zh-hant/com.aspose.slides/doublechartvalue/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

表示可以以兩種方式儲存在 pptx 簡報文件中的 double 值：1) 在與圖表相關的工作簿的儲存格/儲存格中；2) 作為文字值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsCell()](#getAsCell--) | 取得或設定圖表資料儲存格。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 取得或設定圖表資料儲存格。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 取得或設定值為文字 double。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 取得或設定值為文字 double。 |
| [getData()](#getData--) | 取得或設定 Data 物件。 |
| [setData(Object value)](#setData-java.lang.Object-) | 取得或設定 Data 物件。 |
| [toDouble()](#toDouble--) | 轉換為 double。 |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

取得或設定圖表資料儲存格。讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**回傳值:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

取得或設定圖表資料儲存格。讀寫 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

取得或設定值為文字 double。讀寫 double。

**回傳值:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

取得或設定值為文字 double。讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

取得或設定 Data 物件。讀寫 Object。

**回傳值:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

取得或設定 Data 物件。讀寫 Object。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

轉換為 double。

**回傳值:**
double - 若 DataSourceType 為 DoubleLiterals，則回傳 LiteralDouble。若 DataSourceType 為 Worksheet，則回傳成功轉換為 double 的儲存格值，否則回傳 NaN。