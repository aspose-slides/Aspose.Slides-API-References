---
title: DataLabelFormat
second_title: Aspose.Slides for Java API 参考
description: 表示 DataLabel 的格式设置选项。
type: docs
url: /zh/com.aspose.slides/datalabelformat/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**全部已实现的接口：**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

表示 DataLabel 的格式选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 读/写 布尔。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 读/写 布尔。 |
| [getNumberFormat()](#getNumberFormat--) | 表示 DataLabels 对象的格式字符串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 表示 DataLabels 对象的格式字符串。 |
| [getFormat()](#getFormat--) | 表示数据标签的格式。 |
| [getPosition()](#getPosition--) | 表示数据标签的位置。 |
| [setPosition(int value)](#setPosition-int-) | 表示数据标签的位置。 |
| [getShowLegendKey()](#getShowLegendKey--) | 表示指定图表的数据标签图例键显示行为。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 表示指定图表的数据标签图例键显示行为。 |
| [getShowValue()](#getShowValue--) | 表示指定图表的数据标签百分比值显示行为。 |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 表示指定图表的数据标签百分比值显示行为。 |
| [getShowCategoryName()](#getShowCategoryName--) | 表示指定图表的数据标签类别名称显示行为。 |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 表示指定图表的数据标签类别名称显示行为。 |
| [getShowSeriesName()](#getShowSeriesName--) | 返回或设置布尔值，以指示图表上数据标签的系列名称显示行为。 |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | 返回或设置布尔值，以指示图表上数据标签的系列名称显示行为。 |
| [getShowPercentage()](#getShowPercentage--) | 表示指定图表的数据标签百分比值显示行为。 |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 表示指定图表的数据标签百分比值显示行为。 |
| [getShowBubbleSize()](#getShowBubbleSize--) | 表示指定图表的数据标签气泡大小值显示行为。 |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 表示指定图表的数据标签气泡大小值显示行为。 |
| [getShowLeaderLines()](#getShowLeaderLines--) | 表示指定图表的数据标签引导线显示行为。 |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 表示指定图表的数据标签引导线显示行为。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 表示指定图表的数据标签单元格值显示行为。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 表示指定图表的数据标签单元格值显示行为。 |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| [getSeparator()](#getSeparator--) | 设置或返回表示在图表上用于数据标签的分隔符的 Variant。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | 设置或返回表示在图表上用于数据标签的分隔符的 Variant。 |
| [getTextFormat()](#getTextFormat--) | 返回图表文本格式。 |
| [getChart()](#getChart--) | 返回图表。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long.

**返回：**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

读/写 布尔。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 IsNumberFormatLinkedToSource 属性（例如 “DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);” 会导致所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等于 val）。

**返回：**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

读/写 布尔。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 IsNumberFormatLinkedToSource 属性（例如 “DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);” 会导致所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

表示 DataLabels 对象的格式字符串。读/写 String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 NumberFormat 属性的默认值。当使用该属性设置值时，该值也会被设置到 DataLabelCollection 中所有数据标签的 NumberFormat 属性（例如 “DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);” 会导致所有 DataLabels.get_Item(i).getNumberFormat() 等于 val）。

**返回：**
java.lang.String

### setNumberFormat(java.lang.String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

表示 DataLabels 对象的格式字符串。读/写 String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 NumberFormat 属性的默认值。当使用该属性设置值时，该值也会被设置到 DataLabelCollection 中所有数据标签的 NumberFormat 属性（例如 “DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);” 会导致所有 DataLabels.get_Item(i).getNumberFormat() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示数据标签的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性表示 DataLabelCollection 中新数据标签的默认格式。

**返回：**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

表示数据标签的位置。读/写 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Position 属性的默认值。表示 DataLabel 对象的位置。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 Position 属性（例如 “DataLabels.getDefaultDataLabelFormat().setPosition(val);” 会导致所有 DataLabels.get_Item(i).getPosition() 等于 val）。

**返回：**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

表示数据标签的位置。读/写 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Position 属性的默认值。表示 DataLabel 对象的位置。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 Position 属性（例如 “DataLabels.getDefaultDataLabelFormat().setPosition(val);” 会导致所有 DataLabels.get_Item(i).getPosition() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

表示指定图表的数据标签图例键显示行为。如果数据标签图例键可见，则为 True。读/写 布尔。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLegendKey 属性的默认值。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLegendKey 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);” 会导致所有 DataLabels.get_Item(i).getShowLegendKey() 等于 val）。

**返回：**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

表示指定图表的数据标签图例键显示行为。如果数据标签图例键可见，则为 True。读/写 布尔。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLegendKey 属性的默认值。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLegendKey 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);” 会导致所有 DataLabels.get_Item(i).getShowLegendKey() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

表示指定图表的数据标签百分比值显示行为。True 显示百分比值。False 隐藏。读/写 布尔。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowValue 属性的默认值。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowValue 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowValue(val);” 会导致所有 DataLabels.get_Item(i).getShowValue() 等于 val）。

**返回：**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

表示指定图表的数据标签百分比值显示行为。True 显示百分比值。False 隐藏。读/写 布尔。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowValue 属性的默认值。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowValue 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowValue(val);” 会导致所有 DataLabels.get_Item(i).getShowValue() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

表示指定图表的数据标签类别名称显示行为。True 显示类别名称。False 隐藏。读/写 布尔。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowCategoryName 属性的默认值。使用该属性的值进行设置时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowCategoryName 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);” 会导致所有 DataLabels.get_Item(i).getShowCategoryName() 等于 val）。

**返回：**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

表示指定图表的数据标签类别名称显示行为。True 显示类别名称。False 隐藏。读/写 布尔。

--------------------
如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowCategoryName 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowCategoryName 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 导致所有 DataLabels.get_Item(i).getShowCategoryName() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

返回或设置一个 Boolean，用于指示图表上数据标签的系列名称显示行为。True 表示显示系列名称，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowSeriesName 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowSeriesName 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 导致所有 DataLabels.get_Item(i).getShowSeriesName() 等于 val）。

**返回值:**  
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

返回或设置一个 Boolean，用于指示图表上数据标签的系列名称显示行为。True 表示显示系列名称，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowSeriesName 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowSeriesName 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 导致所有 DataLabels.get_Item(i).getShowSeriesName() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowPercentage 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowPercentage 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 导致所有 DataLabels.get_Item(i).getShowPercentage() 等于 val）。

**返回值:**  
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowPercentage 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowPercentage 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 导致所有 DataLabels.get_Item(i).getShowPercentage() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

表示指定图表的数据标签气泡大小值的显示行为。True 表示显示气泡大小值，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowBubbleSize 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowBubbleSize 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 导致所有 DataLabels.get_Item(i).getShowBubbleSize() 等于 val）。

**返回值:**  
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

表示指定图表的数据标签气泡大小值的显示行为。True 表示显示气泡大小值，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowBubbleSize 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowBubbleSize 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 导致所有 DataLabels.get_Item(i).getShowBubbleSize() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

表示指定图表的数据标签引导线的显示行为。True 表示显示引导线，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLeaderLines 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLeaderLines 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 导致所有 DataLabels.get_Item(i).getShowLeaderLines() 等于 val）。

**返回值:**  
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

表示指定图表的数据标签引导线的显示行为。True 表示显示引导线，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLeaderLines 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLeaderLines 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 导致所有 DataLabels.get_Item(i).getShowLeaderLines() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

表示指定图表的数据标签单元格值的显示行为。True 表示显示单元格值，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelValueFromCell 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLabelValueFromCell 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 导致所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等于 val）。

**返回值:**  
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

表示指定图表的数据标签单元格值的显示行为。True 表示显示单元格值，False 表示隐藏。可读写 boolean。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelValueFromCell 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLabelValueFromCell 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 导致所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

确定指定图表的数据标签是显示为数据标注还是数据呼出。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelAsDataCallout 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 导致所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等于 val）。

**返回值:**  
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

确定指定图表的数据标签是显示为数据标注还是数据呼出。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelAsDataCallout 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 导致所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

设置或返回一个 Variant，表示图表上数据标签使用的分隔符。可读写 String。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Separator 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 Separator 属性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 导致所有 DataLabels.get_Item(i).getSeparator() 等于 val）。

**返回值:**  
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

设置或返回一个 Variant，表示图表上数据标签使用的分隔符。可读写 String。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Separator 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 Separator 属性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 导致所有 DataLabels.get_Item(i).getSeparator() 等于 val）。
**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回图表文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

返回图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回：**
[IChart](../../com.aspose.slides/ichart)