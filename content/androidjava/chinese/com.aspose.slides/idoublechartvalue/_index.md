---
title: IDoubleChartValue
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示可以以两种方式存储在 pptx 演示文稿中的 double 值：1) 在与图表关联的工作簿的单元格/单元格中；2) 作为文字值。
type: docs
url: /zh/com.aspose.slides/idoublechartvalue/
---
**所有实现的接口：**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

表示可以以两种方式存储在 pptx 演示文稿中的 double 值：1) 在与图表关联的工作簿的单元格/单元格中；2) 作为文字值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 返回或设置文字 double 值，如果 DataSourceType = Charts.DataSourceType.DoubleLiterals。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 返回或设置文字 double 值，如果 DataSourceType = Charts.DataSourceType.DoubleLiterals。 |
| [toDouble()](#toDouble--) | 转换为 double。 |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

返回或设置文字 double 值，如果 DataSourceType = Charts.DataSourceType.DoubleLiterals。 读/写 double。

**返回：**
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

返回或设置文字 double 值，如果 DataSourceType = Charts.DataSourceType.DoubleLiterals。 读/写 double。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

转换为 double。

**返回：**
double - Double 值。