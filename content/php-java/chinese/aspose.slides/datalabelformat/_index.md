---
title: DataLabelFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/datalabelformat/
---
## DataLabelFormat 类

 表示 DataLabel 的格式选项。
 
### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | 返回图表。只读 IChart。 |

 **返回：**
[Chart](../chart)


---


### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | 表示数据标签的格式。只读 IFormat。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性表示 DataLabelCollection 集合中新数据标签的默认格式。 |

 **返回：**
[Format](../format)


---


### getNumberFormat {#getNumberFormat}

| Name | Description |
| --- | --- |
| getNumberFormat () | 表示 DataLabels 对象的格式字符串。读写 String。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 NumberFormat 属性的默认值。 当使用某个值设置此属性时，该值也会设置为 DataLabelCollection 集合中所有数据标签的 NumberFormat 属性（即 "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" 会导致所有 DataLabels.get_Item(i).getNumberFormat() 等于该值）。 |

 **返回：**
String


---


### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | 表示数据标签的位置。读写 LegendDataLabelPosition。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 Position 属性的默认值。 表示 DataLabel 对象的位置。使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 Position 属性（即 "DataLabels.getDefaultDataLabelFormat().setPosition(val);" 会导致所有 DataLabels.get_Item(i).getPosition() 等于该值）。 |

 **返回：**
int


---


### getSeparator {#getSeparator}

| Name | Description |
| --- | --- |
| getSeparator () | 设置或返回表示图表上数据标签分隔符的 Variant。读写 String。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 Separator 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 Separator 属性（即 "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 会导致所有 DataLabels.get_Item(i).getSeparator() 等于该值）。 |

 **返回：**
String


---


### getShowBubbleSize {#getShowBubbleSize}

| Name | Description |
| --- | --- |
| getShowBubbleSize () | 表示指定图表的数据标签气泡大小值的显示行为。True 表示显示气泡大小值，False 表示隐藏。读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowBubbleSize 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowBubbleSize 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 会导致所有 DataLabels.get_Item(i).getShowBubbleSize() 等于该值）。 |

 **返回：**
boolean


---


### getShowCategoryName {#getShowCategoryName}

| Name | Description |
| --- | --- |
| getShowCategoryName () | 表示指定图表的数据标签类别名称的显示行为。True 表示显示类别名称，False 表示隐藏。读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowCategoryName 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowCategoryName 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 会导致所有 DataLabels.get_Item(i).getShowCategoryName() 等于该值）。 |

 **返回：**
boolean


---


### getShowLabelAsDataCallout {#getShowLabelAsDataCallout}

| Name | Description |
| --- | --- |
| getShowLabelAsDataCallout () | 确定指定图表的数据标签是显示为数据标注还是作为数据标签。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowLabelAsDataCallout 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowLabelAsDataCallout 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 会导致所有 DataLabels.get_Item(i).getShowLabelAsDataCallout() 等于该值）。 |

 **返回：**
boolean


---


### getShowLabelValueFromCell {#getShowLabelValueFromCell}

| Name | Description |
| --- | --- |
| getShowLabelValueFromCell () | 表示指定图表的数据标签单元格值的显示行为。True 显示单元格值，False 隐藏。读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowLabelValueFromCell 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowLabelValueFromCell 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 会导致所有 DataLabels.get_Item(i).getShowLabelValueFromCell() 等于该值）。 |

 **返回：**
boolean


---


### getShowLeaderLines {#getShowLeaderLines}

| Name | Description |
| --- | --- |
| getShowLeaderLines () | 表示指定图表的数据标签引导线的显示行为。True 显示引导线，False 隐藏。读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowLeaderLines 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowLeaderLines 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 会导致所有 DataLabels.get_Item(i).getShowLeaderLines() 等于该值）。 |

 **返回：**
boolean


---


### getShowLegendKey {#getShowLegendKey}

| Name | Description |
| --- | --- |
| getShowLegendKey () | 表示指定图表的数据标签图例键的显示行为。True 表示图例键可见。读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowLegendKey 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowLegendKey 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" 会导致所有 DataLabels.get_Item(i).getShowLegendKey() 等于该值）。 |

 **返回：**
boolean


---


### getShowPercentage {#getShowPercentage}

| Name | Description |
| --- | --- |
| getShowPercentage () | 表示指定图表的数据标签百分比值的显示行为。True 显示百分比值，False 隐藏。读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowPercentage 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowPercentage 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 会导致所有 DataLabels.get_Item(i).getShowPercentage() 等于该值）。 |

 **返回：**
boolean


---


### getShowSeriesName {#getShowSeriesName}

| Name | Description |
| --- | --- |
| getShowSeriesName () | 返回或设置一个 Boolean，以指示图表上数据标签的系列名称显示行为。True 显示系列名称，False 隐藏。读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowSeriesName 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowSeriesName 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 会导致所有 DataLabels.get_Item(i).getShowSeriesName() 等于该值）。 |

 **返回：**
boolean


---


### getShowValue {#getShowValue}

| Name | Description |
| --- | --- |
| getShowValue () | 表示指定图表的数据标签值的显示行为。True 显示该值，False 隐藏。读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 ShowValue 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 ShowValue 属性（即 "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" 会导致所有 DataLabels.get_Item(i).getShowValue() 等于该值）。 |

 **返回：**
boolean


---


### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | 返回图表文本格式。只读 IChartTextFormat。 |

 **返回：**
[ChartTextFormat](../charttextformat)


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **返回：**
long


---


### isNumberFormatLinkedToSource {#isNumberFormatLinkedToSource}

| Name | Description |
| --- | --- |
| isNumberFormatLinkedToSource () | 读写 boolean。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。 使用该值设置此属性时，也会将此值设置为 DataLabelCollection 集合中所有数据标签的 IsNumberFormatLinkedToSource 属性（即 "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" 会导致所有 DataLabels.get_Item(i).isNumberFormatLinkedToSource() 等于该值）。 |

 **返回：**
boolean


---


### setNumberFormat {#setNumberFormat}

| Name | Description |
| --- | --- |
| setNumberFormat (String) | 表示 DataLabels 对象的格式字符串。读写 String。 如果此 DataLabelFormat 对象的父对象是 DataLabelCollection 数据标签集合，则此属性获取或设置 DataLabelCollection 集合中新数据标签的 NumberFormat 属性的默认值。 当使用某个值设置此属性时，该值也会设置为 DataLabelCollection 集合中所有数据标签的 NumberFormat 属性（即 "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" 会导致所有 DataLabels.get_Item(i).getNumberFormat() 等于该值）。 |

 **返回：**
void


---
### setNumberFormatLinkedToSource {#setNumberFormatLinkedToSource}

| 名称 | 描述 |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | 读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 IsNumberFormatLinkedToSource 属性（即 `"DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);"` 导致所有 `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` 等于 val）。 |

**返回值:**  
void


---


### setPosition {#setPosition}

| 名称 | 描述 |
| --- | --- |
| setPosition (int) | 表示数据标签的位置。读/写 LegendDataLabelPosition。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Position 属性的默认值。表示 DataLabel 对象的位置。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 Position 属性（即 `"DataLabels.getDefaultDataLabelFormat().setPosition(val);"` 导致所有 `DataLabels.get_Item(i).getPosition()` 等于 val）。 |

**返回值:**  
void


---


### setSeparator {#setSeparator}

| 名称 | 描述 |
| --- | --- |
| setSeparator (String) | 设置或返回表示图表数据标签使用的分隔符的 Variant。读/写 String。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 Separator 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 Separator 属性（即 `"DataLabels.getDefaultDataLabelFormat().setSeparator(val);"` 导致所有 `DataLabels.get_Item(i).getSeparator()` 等于 val）。 |

**返回值:**  
void


---


### setShowBubbleSize {#setShowBubbleSize}

| 名称 | 描述 |
| --- | --- |
| setShowBubbleSize (boolean) | 表示指定图表的数据标签气泡大小值的显示行为。true 表示显示气泡大小值，false 表示隐藏。读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowBubbleSize 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowBubbleSize 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);"` 导致所有 `DataLabels.get_Item(i).getShowBubbleSize()` 等于 val）。 |

**返回值:**  
void


---


### setShowCategoryName {#setShowCategoryName}

| 名称 | 描述 |
| --- | --- |
| setShowCategoryName (boolean) | 表示指定图表的数据标签类别名称的显示行为。true 表示显示类别名称，false 表示隐藏。读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowCategoryName 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowCategoryName 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);"` 导致所有 `DataLabels.get_Item(i).getShowCategoryName()` 等于 val）。 |

**返回值:**  
void


---


### setShowLabelAsDataCallout {#setShowLabelAsDataCallout}

| 名称 | 描述 |
| --- | --- |
| setShowLabelAsDataCallout (boolean) | 确定指定图表的数据标签是显示为数据呼出框还是普通数据标签。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelAsDataCallout 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLabelAsDataCallout 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);"` 导致所有 `DataLabels.get_Item(i).getShowLabelAsDataCallout()` 等于 val）。 |

**返回值:**  
void


---


### setShowLabelValueFromCell {#setShowLabelValueFromCell}

| 名称 | 描述 |
| --- | --- |
| setShowLabelValueFromCell (boolean) | 表示指定图表的数据标签单元格值的显示行为。true 表示显示单元格值，false 表示隐藏。读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLabelValueFromCell 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLabelValueFromCell 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);"` 导致所有 `DataLabels.get_Item(i).getShowLabelValueFromCell()` 等于 val）。 |

**返回值:**  
void


---


### setShowLeaderLines {#setShowLeaderLines}

| 名称 | 描述 |
| --- | --- |
| setShowLeaderLines (boolean) | 表示指定图表的数据标签指引线的显示行为。true 表示显示指引线，false 表示隐藏。读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLeaderLines 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLeaderLines 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);"` 导致所有 `DataLabels.get_Item(i).getShowLeaderLines()` 等于 val）。 |

**返回值:**  
void


---


### setShowLegendKey {#setShowLegendKey}

| 名称 | 描述 |
| --- | --- |
| setShowLegendKey (boolean) | 表示指定图表的数据标签图例键的显示行为。true 表示图例键可见。读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowLegendKey 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowLegendKey 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);"` 导致所有 `DataLabels.get_Item(i).getShowLegendKey()` 等于 val）。 |

**返回值:**  
void


---


### setShowPercentage {#setShowPercentage}

| 名称 | 描述 |
| --- | --- |
| setShowPercentage (boolean) | 表示指定图表的数据标签百分比值的显示行为。true 表示显示百分比值，false 表示隐藏。读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowPercentage 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowPercentage 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);"` 导致所有 `DataLabels.get_Item(i).getShowPercentage()` 等于 val）。 |

**返回值:**  
void


---


### setShowSeriesName {#setShowSeriesName}

| 名称 | 描述 |
| --- | --- |
| setShowSeriesName (boolean) | 返回或设置一个 Boolean，指示图表数据标签的系列名称显示行为。true 表示显示系列名称，false 表示隐藏。读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowSeriesName 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowSeriesName 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);"` 导致所有 `DataLabels.get_Item(i).getShowSeriesName()` 等于 val）。 |

**返回值:**  
void


---


### setShowValue {#setShowValue}

| 名称 | 描述 |
| --- | --- |
| setShowValue (boolean) | 表示指定图表的数据标签数值的显示行为。true 表示显示数值，false 表示隐藏。读/写 boolean。如果此 DataLabelFormat 对象的父对象是 DataLabelCollection（数据标签集合），则此属性获取或设置 DataLabelCollection 中新数据标签的 ShowValue 属性的默认值。使用该属性并赋值时，还会将此值设置为 DataLabelCollection 中所有数据标签的 ShowValue 属性（即 `"DataLabels.getDefaultDataLabelFormat().setShowValue(val);"` 导致所有 `DataLabels.get_Item(i).getShowValue()` 等于 val）。 |

**返回值:**  
void


---