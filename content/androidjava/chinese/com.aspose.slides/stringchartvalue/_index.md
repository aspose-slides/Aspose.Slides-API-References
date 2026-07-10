---
title: StringChartValue
second_title: Aspose.Slides for Android via Java API 参考
description: 表示可以在 pptx 演示文稿中以两种方式存储的字符串值：1）在与图表关联的工作簿的单元格/单元格中；2）作为字面值。
type: docs
url: /zh/com.aspose.slides/stringchartvalue/
---
**继承：**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**所有实现的接口：**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

表示可以在 pptx 演示文稿中以两种方式存储的字符串值：1) 在与图表关联的工作簿的单元格/单元格中；2) 作为字面值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsCells()](#getAsCells--) | 不允许赋予 null 值。 |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | 不允许赋予 null 值。 |
| [getAsLiteralString()](#getAsLiteralString--) | 返回或设置字面字符串值。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 返回或设置字面字符串值。 |
| [getData()](#getData--) | 返回或设置 Data 对象。 |
| [setData(Object value)](#setData-java.lang.Object-) | 返回或设置 Data 对象。 |
| [toString()](#toString--) | 返回字符串值数据。 |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 从指定单元格设置值。 |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | 如果 DataSourceType 属性为 DataSourceType.Worksheet，则此方法返回工作簿中表示字符串数据的单元格地址。 |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

不允许赋予 null 值。返回的值始终非 null。读/写 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)。

**返回：**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

不允许赋予 null 值。返回的值始终非 null。读/写 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

返回或设置字面字符串值。读/写 String。

**返回：**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

返回或设置字面字符串值。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

返回或设置 Data 对象。读/写 Object。

**返回：**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

返回或设置 Data 对象。读/写 Object。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

返回字符串值数据。如果 DataSourceType 为 false 且未分配字符串值，则返回 null。

**返回：**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

从指定单元格设置值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 单元格。 |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

如果 DataSourceType 属性为 DataSourceType.Worksheet，则此方法返回工作簿中表示字符串数据的单元格地址。否则返回空字符串。

**返回：**
java.lang.String