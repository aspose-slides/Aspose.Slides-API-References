---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for Android via Java API 参考
description: 表示可以存储在 pptx 演示文稿中的字符串或双精度值，有两种方式：1）在与图表关联的工作簿的单元格/单元格中；2）作为文字值。
type: docs
url: /zh/com.aspose.slides/stringordoublechartvalue/
---
**继承:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**所有实现的接口:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

表示可以存储在 pptx 演示文稿中的字符串或双精度值，有两种方式：1) 在与图表关联的工作簿的单元格/单元格中；2) 作为文字值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsCell()](#getAsCell--) | 返回或设置图表数据单元格。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 返回或设置图表数据单元格。 |
| [getAsLiteralString()](#getAsLiteralString--) | 返回或设置值作为文字字符串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 返回或设置值作为文字字符串。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 返回或设置值作为文字双精度。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 返回或设置值作为文字双精度。 |
| [getData()](#getData--) | 返回或设置 Data 对象。 |
| [setData(Object value)](#setData-java.lang.Object-) | 返回或设置 Data 对象。 |
| [toDouble()](#toDouble--) | 转换为双精度。 |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

返回或设置图表数据单元格。读/写 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**返回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

返回或设置图表数据单元格。读/写 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

返回或设置值作为文字字符串。读/写 String。

**返回:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

返回或设置值作为文字字符串。读/写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

返回或设置值作为文字双精度。读/写 double。

**返回:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

返回或设置值作为文字双精度。读/写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

返回或设置 Data 对象。读/写 Object。

**返回:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

返回或设置 Data 对象。读/写 Object。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

转换为双精度。

**返回:**
double - 双精度值。