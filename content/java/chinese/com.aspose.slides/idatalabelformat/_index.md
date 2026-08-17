---
title: IDataLabelFormat
second_title: Aspose.Slides 的 Java API 参考
description: 表示 DataLabel 的格式化选项。
type: docs
url: /zh/com.aspose.slides/idatalabelformat/
---
**所有实现的接口：**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

表示 DataLabel 的格式选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 可读写布尔值。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 可读写布尔值。 |
| [getNumberFormat()](#getNumberFormat--) | 表示 DataLabels 对象的格式字符串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 表示 DataLabels 对象的格式字符串。 |
| [getFormat()](#getFormat--) | 表示数据标签的格式。 |
| [getPosition()](#getPosition--) | 表示数据标签的位置。 |
| [setPosition(int value)](#setPosition-int-) | 表示数据标签的位置。 |
| [getShowLegendKey()](#getShowLegendKey--) | 表示指定图表的数据标签图例键的显示行为。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 表示指定图表的数据标签图例键的显示行为。 |
| [getShowValue()](#getShowValue--) | 表示指定图表的数据标签百分比值的显示行为。 |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 表示指定图表的数据标签百分比值的显示行为。 |
| [getShowCategoryName()](#getShowCategoryName--) | 表示指定图表的数据标签类别名称的显示行为。 |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 表示指定图表的数据标签类别名称的显示行为。 |
| [getShowSeriesName()](#getShowSeriesName--) | 返回或设置布尔值，以指示图表上数据标签的系列名称显示行为。 |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | 返回或设置布尔值，以指示图表上数据标签的系列名称显示行为。 |
| [getShowPercentage()](#getShowPercentage--) | 表示指定图表的数据标签百分比值的显示行为。 |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 表示指定图表的数据标签百分比值的显示行为。 |
| [getShowBubbleSize()](#getShowBubbleSize--) | 表示指定图表的数据标签气泡大小值的显示行为。 |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 表示指定图表的数据标签气泡大小值的显示行为。 |
| [getShowLeaderLines()](#getShowLeaderLines--) | 表示指定图表的数据标签引导线的显示行为。 |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 表示指定图表的数据标签引导线的显示行为。 |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 表示指定图表的数据标签单元格值的显示行为。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 表示指定图表的数据标签单元格值的显示行为。 |
| [getSeparator()](#getSeparator--) | 设置或返回表示图表上数据标签使用的分隔符的 Variant。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | 设置或返回表示图表上数据标签使用的分隔符的 Variant。 |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

可读写布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 IsNumberFormatLinkedToSource 属性（例如 “DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);” 会导致所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等于 val）。

**返回:** boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

可读写布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 IsNumberFormatLinkedToSource 属性（例如 “DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);” 会导致所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

表示 DataLabels 对象的格式字符串。可读写字符串。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 NumberFormat 属性的默认值。当此属性设置了一个值时，该值也会设置为 DataLabelCollection 中所有数据标签的 NumberFormat 属性（例如 “DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);” 会导致所有 DataLabels.get_Item(i).getNumberFormat() 等于 val）。

**返回:** java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

表示 DataLabels 对象的格式字符串。可读写字符串。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 NumberFormat 属性的默认值。当此属性设置了一个值时，该值也会设置为 DataLabelCollection 中所有数据标签的 NumberFormat 属性（例如 “DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);” 会导致所有 DataLabels.get_Item(i).getNumberFormat() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示数据标签的格式。只读 [IFormat](../../com.aspose.slides/iformat)。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性表示新数据标签的默认格式。

**返回:** [IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

表示数据标签的位置。可读写 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Position 属性的默认值。表示 DataLabel 对象的位置。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 Position 属性（例如 “DataLabels.getDefaultDataLabelFormat().setPosition(val)” 会导致所有 DataLabels.get_Item(i).getPosition() 等于 val）。

**返回:** int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

表示数据标签的位置。可读写 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Position 属性的默认值。表示 DataLabel 对象的位置。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 Position 属性（例如 “DataLabels.getDefaultDataLabelFormat().setPosition(val)” 会导致所有 DataLabels.get_Item(i).getPosition() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

表示指定图表的数据标签图例键的显示行为。如果数据标签图例键可见则为 True。可读写布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLegendKey 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLegendKey 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);” 会导致所有 DataLabels.get_Item(i).getShowLegendKey() 等于 val）。

**返回:** boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

表示指定图表的数据标签图例键的显示行为。如果数据标签图例键可见则为 True。可读写布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLegendKey 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLegendKey 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);” 会导致所有 DataLabels.get_Item(i).getShowLegendKey() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

表示指定图表的数据标签百分比值的显示行为。True 时显示百分比值，False 时隐藏。可读写布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowValue 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowValue 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowValue(val);” 会导致所有 DataLabels.get_Item(i).getShowValue() 等于 val）。

**返回:** boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

表示指定图表的数据标签百分比值的显示行为。True 时显示百分比值，False 时隐藏。可读写布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowValue 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowValue 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowValue(val);” 会导致所有 DataLabels.get_Item(i).getShowValue() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

表示指定图表的数据标签类别名称的显示行为。True 时显示图表上数据标签的类别名称，False 时隐藏。可读写布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowCategoryName 属性的默认值。使用该属性设置值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowCategoryName 属性（例如 “DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);” 会导致所有 DataLabels.get_Item(i).getShowCategoryName() 等于 val）。

**返回:** boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

表示指定图表的数据标签类别名称的显示行为。True 时显示图表上数据标签的类别名称，False 时隐藏。可读写布尔值。

--------------------
如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowCategoryName 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowCategoryName 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 导致所有 DataLabels.get_Item(i).getShowCategoryName() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

返回或设置布尔值，以指示图表上数据标签的系列名称显示行为。True 表示显示系列名称。False 表示隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowSeriesName 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowSeriesName 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 导致所有 DataLabels.get_Item(i).getShowSeriesName() 等于 val）。

**返回值：**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

返回或设置布尔值，以指示图表上数据标签的系列名称显示行为。True 表示显示系列名称。False 表示隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowSeriesName 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowSeriesName 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 导致所有 DataLabels.get_Item(i).getShowSeriesName() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

表示指定图表的数据标签百分比值的显示行为。True 显示百分比值。False 隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowPercentage 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowPercentage 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 导致所有 DataLabels.get_Item(i).getShowPercentage() 等于 val）。

**返回值：**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

表示指定图表的数据标签百分比值的显示行为。True 显示百分比值。False 隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowPercentage 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowPercentage 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 导致所有 DataLabels.get_Item(i).getShowPercentage() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

表示指定图表的数据标签气泡大小值的显示行为。True 显示气泡大小值。False 隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowBubbleSize 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowBubbleSize 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 导致所有 DataLabels.get_Item(i).getShowBubbleSize() 等于 val）。

**返回值：**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

表示指定图表的数据标签气泡大小值的显示行为。True 显示气泡大小值。False 隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowBubbleSize 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowBubbleSize 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 导致所有 DataLabels.get_Item(i).getShowBubbleSize() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

表示指定图表的数据标签引导线的显示行为。True 显示引导线。False 隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLeaderLines 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowLeaderLines 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 导致所有 DataLabels.get_Item(i).getShowLeaderLines() 等于 val）。

**返回值：**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

表示指定图表的数据标签引导线的显示行为。True 显示引导线。False 隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLeaderLines 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowLeaderLines 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 导致所有 DataLabels.get_Item(i).getShowLeaderLines() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

确定指定图表的数据标签是显示为数据标注还是显示为数据标签。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelAsDataCallout 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 导致所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等于 val）。

**返回值：**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

确定指定图表的数据标签是显示为数据标注还是显示为数据标签。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelAsDataCallout 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 导致所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

表示指定图表的数据标签单元格值的显示行为。True 显示单元格值。False 隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelValueFromCell 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowLabelValueFromCell 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 导致所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等于 val）。

**返回值：**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

表示指定图表的数据标签单元格值的显示行为。True 显示单元格值。False 隐藏。读/写 boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelValueFromCell 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 ShowLabelValueFromCell 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 导致所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等于 val）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

设置或返回表示图表上数据标签使用的分隔符的 Variant。读/写 String.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Separator 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 Separator 属性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 导致所有 DataLabels.get_Item(i).getSeparator() 等于 val）。

**返回值：**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

设置或返回表示图表上数据标签使用的分隔符的 Variant。读/写 String.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Separator 属性的默认值。使用 value 设置此属性时，还会将该值设置为 DataLabelCollection 中所有数据标签的 Separator 属性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 导致所有 DataLabels.get_Item(i).getSeparator() 等于 val）。
**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |