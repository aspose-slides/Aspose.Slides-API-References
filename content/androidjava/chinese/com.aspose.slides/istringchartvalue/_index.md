---
title: IStringChartValue
second_title: Aspose.Slides for Android via Java API 参考
description: 表示可以以两种方式存储在 PPTX 演示文稿中的字符串值：1）在与图表关联的工作簿的单元格/单元格中；2）作为字面值。
type: docs
url: /zh/com.aspose.slides/istringchartvalue/
---
**已实现的接口:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

表示可以以两种方式存储在 pptx 演示文稿中的字符串值：1) 在与图表关联的工作簿的单元格/单元格中；2) 作为字面值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | 如果 DataSourceType 属性为 DataSourceType.StringLiterals，则返回或设置文字字符串。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 如果 DataSourceType 属性为 DataSourceType.StringLiterals，则返回或设置文字字符串。 |
| [toString()](#toString--) | 返回字符串表示。 |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 从指定单元格设置值。 |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | 如果 DataSourceType 属性为 DataSourceType.Worksheet，则此方法返回工作簿中表示字符串数据的单元格地址。 |

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

### toString() {#toString--}
```
public abstract String toString()
```

返回字符串表示。

**返回:**
java.lang.String - 值的字符串表示 String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

从指定单元格设置值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

如果 DataSourceType 属性为 DataSourceType.Worksheet，则此方法返回工作簿中表示字符串数据的单元格地址。否则返回空字符串。

**返回:**
java.lang.String - 字符串值 String