---
title: DataLabelFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/datalabelformat/
---

## DataLabelFormat class

 Represents formatting options for DataLabel.
 

## Methods

| Name | Description |
| --- | --- |
| [getChart](getchart)() | Returns the chart. Read-only IChart. |
| [getFormat](getformat)() | Represents the format of the data label. Read-only IFormat. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property represents the default format for the new data labels in the DataLabelCollection collection. |
| [getNumberFormat](getnumberformat)() | Represents the format string for the DataLabels object. Read/write String. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val). |
| [getPosition](getposition)() | Represents the position of the data label. Read/write LegendDataLabelPosition. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause to all DataLabels.get_Item(i).getPosition() is equal to val). |
| [getSeparator](getseparator)() | Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val). |
| [getShowBubbleSize](getshowbubblesize)() | Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val). |
| [getShowCategoryName](getshowcategoryname)() | Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val). |
| [getShowLabelAsDataCallout](getshowlabelasdatacallout)() | Determines either specified chart's data label will be displayed as data callout or as data label. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val). |
| [getShowLabelValueFromCell](getshowlabelvaluefromcell)() | Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val). |
| [getShowLeaderLines](getshowleaderlines)() | Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val). |
| [getShowLegendKey](getshowlegendkey)() | Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val). |
| [getShowPercentage](getshowpercentage)() | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val). |
| [getShowSeriesName](getshowseriesname)() | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val). |
| [getShowValue](getshowvalue)() | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val). |
| [getTextFormat](gettextformat)() | Returns chart text format. Read-only IChartTextFormat. |
| [isNumberFormatLinkedToSource](isnumberformatlinkedtosource)() | Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the IsNumberFormatLinkedToSource property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val). |
| [setNumberFormat](setnumberformat)(String) | Represents the format string for the DataLabels object. Read/write String. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val). |
| [setNumberFormatLinkedToSource](setnumberformatlinkedtosource)(boolean) | Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the IsNumberFormatLinkedToSource property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val). |
| [setPosition](setposition)(int) | Represents the position of the data label. Read/write LegendDataLabelPosition. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" cause to all DataLabels.get_Item(i).getPosition() is equal to val). |
| [setSeparator](setseparator)(String) | Sets or returns a Variant representing the separator used for the data labels on a chart. Read/write String. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val). |
| [setShowBubbleSize](setshowbubblesize)(boolean) | Represents a specified chart's data label bubble size value display behavior. True displays the bubble size value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val). |
| [setShowCategoryName](setshowcategoryname)(boolean) | Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val). |
| [setShowLabelAsDataCallout](setshowlabelasdatacallout)(boolean) | Determines either specified chart's data label will be displayed as data callout or as data label. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val). |
| [setShowLabelValueFromCell](setshowlabelvaluefromcell)(boolean) | Represents a specified chart's data label cell value display behavior. True displays cell value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val). |
| [setShowLeaderLines](setshowleaderlines)(boolean) | Represents a specified chart's data label leader lines display behavior. True displays the leader lines. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val). |
| [setShowLegendKey](setshowlegendkey)(boolean) | Represents a specified chart's data label legend key display behavior. True if the data label legend key is visible. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val). |
| [setShowPercentage](setshowpercentage)(boolean) | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val). |
| [setShowSeriesName](setshowseriesname)(boolean) | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val). |
| [setShowValue](setshowvalue)(boolean) | Represents a specified chart's data label percentage value display behavior. True displays the percentage value. False to hide. Read/write boolean. If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val). |