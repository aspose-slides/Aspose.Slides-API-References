---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Java API 参考
description: 表示可以以两种方式存储在 pptx 演示文稿中的字符串或 double 值：1）在与图表关联的工作簿的单元格/单元格中；2）作为文字值。
type: docs
url: /zh/com.aspose.slides/istringordoublechartvalue/
---
**所有实现的接口:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

表示可以以两种方式存储在 pptx 演示文稿中的字符串或 double 值：1) 在与图表关联的工作簿的单元格/单元格中；2) 作为文字值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | 如果 DataSourceType 属性为 DataSourceType.StringLiterals，则返回或设置文字字符串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 如果 DataSourceType 属性为 DataSourceType.StringLiterals，则返回或设置文字字符串。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 如果 DataSourceType 属性为 DataSourceType.DoubleLiterals，则返回或设置文字 double。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 如果 DataSourceType 属性为 DataSourceType.DoubleLiterals，则返回或设置文字 double。 |
| [toDouble()](#toDouble--) | 将值转换为 double。 |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

如果 DataSourceType 属性为 DataSourceType.StringLiterals，则返回或设置文字字符串。读/写 String。

**返回:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

如果 DataSourceType 属性为 DataSourceType.StringLiterals，则返回或设置文字字符串。读/写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

如果 DataSourceType 属性为 DataSourceType.DoubleLiterals，则返回或设置文字 double。读/写 double。

**返回:**
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

如果 DataSourceType 属性为 DataSourceType.DoubleLiterals，则返回或设置文字 double。读/写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

将值转换为 double。

**返回:**
double - Double 值 double