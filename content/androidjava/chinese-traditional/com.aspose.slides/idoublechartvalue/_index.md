---
title: IDoubleChartValue
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示可在 pptx 簡報文件中以兩種方式儲存的 double 值：1) 在與圖表相關的工作簿儲存格/儲存格中；2) 作為文字值。
type: docs
url: /zh-hant/com.aspose.slides/idoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

表示可在 pptx 簡報文件中以兩種方式儲存的 double 值：1) 在圖表相關工作簿的儲存格/儲存格中；2) 作為文字值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，則取得或設定文字 double 值。可讀寫 double。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，則取得或設定文字 double 值。可讀寫 double。 |
| [toDouble()](#toDouble--) | 轉換為 double。 |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，則取得或設定文字 double 值。可讀寫 double。

**返回：**
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，則取得或設定文字 double 值。可讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

轉換為 double。

**返回：**
double - Double 值。