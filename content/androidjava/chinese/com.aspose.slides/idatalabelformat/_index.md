---
title: IDataLabelFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 DataLabel 的格式设置选项。
type: docs
url: /zh/com.aspose.slides/idatalabelformat/
---
**所有实现的接口:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

表示 DataLabel 的格式设置选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 读取/写入布尔值。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 读取/写入布尔值。 |
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
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 确定指定图表的数据标签是显示为数据标注还是数据标签。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 表示指定图表的数据标签单元格值显示行为。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 表示指定图表的数据标签单元格值显示行为。 |
| [getSeparator()](#getSeparator--) | 设置或返回表示图表上数据标签使用的分隔符的 Variant。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | 设置或返回表示图表上数据标签使用的分隔符的 Variant。 |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

读取/写入布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。使用该值设置此属性还会将此值设置为 DataLabelCollection 中所有数据标签的 IsNumberFormatLinkedToSource 属性（例如 "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" 导致所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等于 val）。

**返回:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

读取/写入布尔值。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。使用该值设置此属性还会将此值设置为 DataLabelCollection 中所有数据标签的 IsNumberFormatLinkedToSource 属性（例如 "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" 导致所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

表示 DataLabels 对象的格式字符串。读取/写入 String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get\_Item(i).getNumberFormat() to equal to val).

**Returns:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```


Represents the format string for the DataLabels object. Read/write String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Represents the format of the data label. Read-only [IFormat](../../com.aspose.slides/iformat).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property represents the default format for the new data labels in the DataLabelCollection collection.

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Represents the position of the data label. Read/write [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Represents the position of the data label. Read/write [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**Returns:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

表示指定图表的数据标签图例键显示行为。如果数据标签图例键可见，则为 true。Read/write boolean.

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLegendKey 属性的默认值。使用该值设置此属性还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLegendKey 属性（例如 "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**Returns:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Returns:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Returns:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Returns:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Returns:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Returns:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Determines either specified chart's data label will be displayed as data callout or as data label.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Returns:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Determines either specified chart's data label will be displayed as data callout or as data label.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Returns:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)

设置或返回表示图表上数据标签使用的分隔符的 Variant。读取/写入 String。

--------------------

如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 中新数据标签的 Separator 属性的默认值。使用该值设置此属性还会将此值设置为 DataLabelCollection 中所有数据标签的 Separator 属性（例如 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 导致所有 DataLabels.get_Item(i).getSeparator() 等于 val）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |