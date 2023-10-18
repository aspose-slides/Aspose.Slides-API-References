---
title: DataLabelFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/datalabelformat/
---

## DataLabelFormat class

 Represents formatting options for DataLabel.
 
### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Returns the chart. Read-only IChart. |

 **Returns:**
[Chart](../chart)


---


### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | Represents the format of the data label. Read-only IFormat. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property represents the default format for the new data labels in the DataLabelCollection collection. |

 **Returns:**
[Format](../format)


---


### getNumberFormat {#getNumberFormat}

| Name | Description |
| --- | --- |
| getNumberFormat () | Represents the format string for the DataLabels object. Read/write String. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val). |

 **Returns:**
String


---


### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | Represents the position of the data label. Read/write LegendDataLabelPosition. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause to all DataLabels.get_Item(i).getPosition() is equal to val). |

 **Returns:**
int


---


### getSeparator {#getSeparator}

| Name | Description |
| --- | --- |
| getSeparator () | Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val). |

 **Returns:**
String


---


### getShowBubbleSize {#getShowBubbleSize}

| Name | Description |
| --- | --- |
| getShowBubbleSize () | Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val). |

 **Returns:**
boolean


---


### getShowCategoryName {#getShowCategoryName}

| Name | Description |
| --- | --- |
| getShowCategoryName () | Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val). |

 **Returns:**
boolean


---


### getShowLabelAsDataCallout {#getShowLabelAsDataCallout}

| Name | Description |
| --- | --- |
| getShowLabelAsDataCallout () | Determines either specified chart's data label will be displayed as data callout or as data label. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val). |

 **Returns:**
boolean


---


### getShowLabelValueFromCell {#getShowLabelValueFromCell}

| Name | Description |
| --- | --- |
| getShowLabelValueFromCell () | Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val). |

 **Returns:**
boolean


---


### getShowLeaderLines {#getShowLeaderLines}

| Name | Description |
| --- | --- |
| getShowLeaderLines () | Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val). |

 **Returns:**
boolean


---


### getShowLegendKey {#getShowLegendKey}

| Name | Description |
| --- | --- |
| getShowLegendKey () | Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val). |

 **Returns:**
boolean


---


### getShowPercentage {#getShowPercentage}

| Name | Description |
| --- | --- |
| getShowPercentage () | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val). |

 **Returns:**
boolean


---


### getShowSeriesName {#getShowSeriesName}

| Name | Description |
| --- | --- |
| getShowSeriesName () | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val). |

 **Returns:**
boolean


---


### getShowValue {#getShowValue}

| Name | Description |
| --- | --- |
| getShowValue () | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val). |

 **Returns:**
boolean


---


### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | Returns chart text format. Read-only IChartTextFormat. |

 **Returns:**
[ChartTextFormat](../charttextformat)


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Returns:**
long


---


### isNumberFormatLinkedToSource {#isNumberFormatLinkedToSource}

| Name | Description |
| --- | --- |
| isNumberFormatLinkedToSource () | Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the IsNumberFormatLinkedToSource property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val). |

 **Returns:**
boolean


---


### setNumberFormat {#setNumberFormat}

| Name | Description |
| --- | --- |
| setNumberFormat (String) | Represents the format string for the DataLabels object. Read/write String. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val). |

 **Returns:**
void


---


### setNumberFormatLinkedToSource {#setNumberFormatLinkedToSource}

| Name | Description |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the IsNumberFormatLinkedToSource property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val). |

 **Returns:**
void


---


### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition (int) | Represents the position of the data label. Read/write LegendDataLabelPosition. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause to all DataLabels.get_Item(i).getPosition() is equal to val). |

 **Returns:**
void


---


### setSeparator {#setSeparator}

| Name | Description |
| --- | --- |
| setSeparator (String) | Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val). |

 **Returns:**
void


---


### setShowBubbleSize {#setShowBubbleSize}

| Name | Description |
| --- | --- |
| setShowBubbleSize (boolean) | Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val). |

 **Returns:**
void


---


### setShowCategoryName {#setShowCategoryName}

| Name | Description |
| --- | --- |
| setShowCategoryName (boolean) | Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val). |

 **Returns:**
void


---


### setShowLabelAsDataCallout {#setShowLabelAsDataCallout}

| Name | Description |
| --- | --- |
| setShowLabelAsDataCallout (boolean) | Determines either specified chart's data label will be displayed as data callout or as data label. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val). |

 **Returns:**
void


---


### setShowLabelValueFromCell {#setShowLabelValueFromCell}

| Name | Description |
| --- | --- |
| setShowLabelValueFromCell (boolean) | Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val). |

 **Returns:**
void


---


### setShowLeaderLines {#setShowLeaderLines}

| Name | Description |
| --- | --- |
| setShowLeaderLines (boolean) | Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val). |

 **Returns:**
void


---


### setShowLegendKey {#setShowLegendKey}

| Name | Description |
| --- | --- |
| setShowLegendKey (boolean) | Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val). |

 **Returns:**
void


---


### setShowPercentage {#setShowPercentage}

| Name | Description |
| --- | --- |
| setShowPercentage (boolean) | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val). |

 **Returns:**
void


---


### setShowSeriesName {#setShowSeriesName}

| Name | Description |
| --- | --- |
| setShowSeriesName (boolean) | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val). |

 **Returns:**
void


---


### setShowValue {#setShowValue}

| Name | Description |
| --- | --- |
| setShowValue (boolean) | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val). |

 **Returns:**
void


---


