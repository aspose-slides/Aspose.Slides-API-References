---
title: DoubleChartValue
second_title: Aspose.Slides for Android via Java API 参考
description: 表示可以以两种方式存储在 pptx 演示文稿中的 double 值：1）在与图表关联的工作簿单元格/单元格中；2）作为字面值。
type: docs
url: /zh/com.aspose.slides/doublechartvalue/
---
**继承:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**全部实现的接口:**  
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)  
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

表示可以以两种方式存储在 pptx 演示文稿中的 double 值：1) 在与图表相关的工作簿的单元格/单元格中；2) 作为字面值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsCell()](#getAsCell--) | 返回或设置图表数据单元格。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 返回或设置图表数据单元格。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 返回或设置字面 double 值。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 返回或设置字面 double 值。 |
| [getData()](#getData--) | 返回或设置 Data 对象。 |
| [setData(Object value)](#setData-java.lang.Object-) | 返回或设置 Data 对象。 |
| [toDouble()](#toDouble--) | 转换为 double。 |

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

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

返回或设置字面 double 值。读/写 double。

**返回:**  
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

返回或设置字面 double 值。读/写 double。

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

转换为 double。

**返回:**  
double - 如果 DataSourceType 等于 DoubleLiterals，则返回 LiteralDouble。若 DataSourceType 等于 Worksheet，则返回成功转换为 double 的单元格值，否则返回 NaN。