---
title: DataLabelFormat
second_title: Aspose.Slides for Java API Reference
description:  Represents formatting options for DataLabel.
type: docs
weight: 149
url: /java/com.aspose.slides/datalabelformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Represents formatting options for DataLabel.
## Methods

| Method | Description |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Read/write boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Read/write boolean. |
| [getNumberFormat()](#getNumberFormat--) | Represents the format string for the DataLabels object. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Represents the format string for the DataLabels object. |
| [getFormat()](#getFormat--) | Represents the format of the data label. |
| [getPosition()](#getPosition--) | Represents the position of the data label. |
| [setPosition(int value)](#setPosition-int-) | Represents the position of the data label. |
| [getShowLegendKey()](#getShowLegendKey--) | Represents a specified chart's data label legend key display behavior. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Represents a specified chart's data label legend key display behavior. |
| [getShowValue()](#getShowValue--) | Represents a specified chart's data label percentage value display behavior. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Represents a specified chart's data label percentage value display behavior. |
| [getShowCategoryName()](#getShowCategoryName--) | Represents a specified chart's data label category name display behavior. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Represents a specified chart's data label category name display behavior. |
| [getShowSeriesName()](#getShowSeriesName--) | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. |
| [getShowPercentage()](#getShowPercentage--) | Represents a specified chart's data label percentage value display behavior. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Represents a specified chart's data label percentage value display behavior. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Represents a specified chart's data label bubble size value display behavior. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Represents a specified chart's data label bubble size value display behavior. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Represents a specified chart's data label leader lines display behavior. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Represents a specified chart's data label leader lines display behavior. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Represents a specified chart's data label cell value display behavior. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Represents a specified chart's data label cell value display behavior. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determines either specified chart's data label will be displayed as data callout or as data label. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determines either specified chart's data label will be displayed as data callout or as data label. |
| [getSeparator()](#getSeparator--) | Sets or returns a Variant representing the separator used for the data labels on a chart. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Sets or returns a Variant representing the separator used for the data labels on a chart. |
| [getTextFormat()](#getTextFormat--) | Returns chart text format. |
| [getChart()](#getChart--) | Returns the chart. |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the IsNumberFormatLinkedToSource property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" cause to all DataLabels.get\_Item(i).isNumberFormatLinkedToSource() is equal to val).

**Returns:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the IsNumberFormatLinkedToSource property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" cause to all DataLabels.get\_Item(i).isNumberFormatLinkedToSource() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Represents the format string for the DataLabels object. Read/write String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. Represents the format string for the DataLabel objects. Set this property with value also sets this value to the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" cause to all DataLabels.get\_Item(i).getNumberFormat() is equal to val).

**Returns:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Represents the format string for the DataLabels object. Read/write String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. Represents the format string for the DataLabel objects. Set this property with value also sets this value to the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" cause to all DataLabels.get\_Item(i).getNumberFormat() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Represents the format of the data label. Read-only [IFormat](../../com.aspose.slides/iformat).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property represents the default format for the new data labels in the DataLabelCollection collection.

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Represents the position of the data label. Read/write [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause to all DataLabels.get\_Item(i).getPosition() is equal to val).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Represents the position of the data label. Read/write [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause to all DataLabels.get\_Item(i).getPosition() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```


Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get\_Item(i).getShowLegendKey() is equal to val).

**Returns:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```


Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get\_Item(i).getShowLegendKey() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```


Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get\_Item(i).getShowValue() is equal to val).

**Returns:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```


Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get\_Item(i).getShowValue() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```


Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get\_Item(i).getShowCategoryName() is equal to val).

**Returns:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```


Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get\_Item(i).getShowCategoryName() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```


Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get\_Item(i).getShowSeriesName() is equal to val).

**Returns:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```


Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get\_Item(i).getShowSeriesName() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```


Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get\_Item(i).getShowPercentage() is equal to val).

**Returns:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```


Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get\_Item(i).getShowPercentage() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```


Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get\_Item(i).getShowBubbleSize() is equal to val).

**Returns:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```


Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get\_Item(i).getShowBubbleSize() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```


Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get\_Item(i).getShowLeaderLines() is equal to val).

**Returns:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```


Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get\_Item(i).getShowLeaderLines() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```


Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get\_Item(i).getShowLabelValueFromCell() is equal to val).

**Returns:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```


Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get\_Item(i).getShowLabelValueFromCell() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```


Determines either specified chart's data label will be displayed as data callout or as data label.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get\_Item(i).getShowLabelAsDataCallout() is equal to val).

**Returns:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```


Determines either specified chart's data label will be displayed as data callout or as data label.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get\_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get\_Item(i).getSeparator() is equal to val).

**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get\_Item(i).getSeparator() is equal to val).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Returns chart text format. Read-only [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returns the chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)