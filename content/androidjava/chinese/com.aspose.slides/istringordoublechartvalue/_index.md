---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示可以以两种方式存储在 pptx 演示文稿中的字符串或双精度值：1）在与图表关联的工作簿的单元格/单元格中；2）作为文字值。
type: docs
url: /zh/com.aspose.slides/istringordoublechartvalue/
---
**所有已实现的接口:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

表示可以以两种方式存储在 pptx 演示文稿中的字符串或双精度数值：1) 在与图表关联的工作簿的单元格/单元格中；2) 作为文字值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets the literal double if DataSourceType property is DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converts value to double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

如果 DataSourceType 属性为 DataSourceType.StringLiterals，则返回或设置文字字符串。读/写 String。

**返回：**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

如果 DataSourceType 属性为 DataSourceType.StringLiterals，则返回或设置文字字符串。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

如果 DataSourceType 属性为 DataSourceType.DoubleLiterals，则返回或设置文字双精度。读/写 double。

**返回：**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

如果 DataSourceType 属性为 DataSourceType.DoubleLiterals，则返回或设置文字双精度。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

将值转换为 double。

**返回：**
double - 双精度值 double