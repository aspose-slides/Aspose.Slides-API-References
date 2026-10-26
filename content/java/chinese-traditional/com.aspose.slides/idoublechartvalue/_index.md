---
title: IDoubleChartValue
second_title: Aspose.Slides for Java API 參考
description: 表示可以以兩種方式儲存在 pptx 簡報文件中的雙精度值：1）在與圖表相關的工作簿之單元格/多個單元格中；2）作為文字值。
type: docs
url: /zh-hant/com.aspose.slides/idoublechartvalue/
---
**所有已实现的接口:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

表示可以以兩種方式儲存在 pptx 簡報文件中的雙精度值：1）在與圖表相關的工作簿之單元格/多個單元格中；2）作為文字值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，則返回或設定文字雙精度值。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，則返回或設定文字雙精度值。 |
| [toDouble()](#toDouble--) | 轉換為 double。 |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，則返回或設定文字雙精度值。可讀寫 double。

**返回:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，則返回或設定文字雙精度值。可讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

轉換為 double。

**返回:**
double - 雙精度值。