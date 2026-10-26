---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Java API 參考文件
description: 表示可儲存在 pptx 簡報文件中的字串或雙精度值，有兩種方式：1）在與圖表相關的工作簿之單元格/多個單元格中；2）作為文字值。
type: docs
url: /zh-hant/com.aspose.slides/istringordoublechartvalue/
---
**所有已實作的介面：**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

表示可儲存在 pptx 簡報文件中的字串或雙精度值，有兩種方式：1）存於與圖表相關的工作簿之單元格/多個單元格中；2）作為文字值。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | 如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則取得或設定文字字串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則取得或設定文字字串。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 如果 DataSourceType 屬性為 DataSourceType.DoubleLiterals，則取得或設定雙精度數值。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 如果 DataSourceType 屬性為 DataSourceType.DoubleLiterals，則取得或設定雙精度數值。 |
| [toDouble()](#toDouble--) | 將值轉換為雙精度。 |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則取得或設定文字字串。可讀寫 String。

**回傳：**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

如果 DataSourceType 屬性為 DataSourceType.StringLiterals，則取得或設定文字字串。可讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

如果 DataSourceType 屬性為 DataSourceType.DoubleLiterals，則取得或設定雙精度數值。可讀寫 double。

**回傳：**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

如果 DataSourceType 屬性為 DataSourceType.DoubleLiterals，則取得或設定雙精度數值。可讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

將值轉換為雙精度。

**回傳：**
double - Double value double