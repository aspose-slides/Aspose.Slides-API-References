---
title: IDoubleChartValue
second_title: Aspose.Slides for Java API 参考
description: 表示可以在 pptx 演示文稿文档中以两种方式存储的 double 值：1）在与 chart 关联的工作簿的 cell/cells 中；2）作为字面值。
type: docs
url: /zh/com.aspose.slides/idoublechartvalue/
---
**所有实现的接口：**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

表示可以在 pptx 演示文稿文档中以两种方式存储的 double 值：1) 在与 chart 关联的工作簿的 cell/cells 中；2) 作为字面值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，则返回或设置字面 double 值。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，则返回或设置字面 double 值。 |
| [toDouble()](#toDouble--) | 转换为 double。 |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，则返回或设置字面 double 值。可读写 double。

**返回值：**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


如果 DataSourceType = Charts.DataSourceType.DoubleLiterals，则返回或设置字面 double 值。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


转换为 double。

**返回值：**
double - Double 值.