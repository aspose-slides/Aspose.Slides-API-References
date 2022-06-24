---
title: DataLabelCollection
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/datalabelcollection/
---

## DataLabelCollection class

 Represents a series labels.
 

## Methods

| Name | Description |
| --- | --- |
| [getChart](getchart)() | Returns the parent chart. Read-only IChart. |
| [getCount](getcount)() | Gets the number of all data labels in the collection. Read-only int. |
| [getCountOfVisibleDataLabels](getcountofvisibledatalabels)() | Gets the number of visible data labels in the collection. Read-only int. |
| [getDefaultDataLabelFormat](getdefaultdatalabelformat)() | Gets the default data label format. Read-only IDataLabelFormat. |
| [getParentSeries](getparentseries)() | Gets the parent series. Read-only IChartSeries. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getSlide](getslide)() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [get_Item](get_item)(int) | Gets the data label for the data point with the specified index. Alternate way to access data label is: - series.getDataPoints().get_Item(i).getLabel() - manage label properties. |
| [hide](hide)() | Make data label hidden by default by setting all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. IsVisible will be false after this. If data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state. |
| [indexOf](indexof)(IDataLabel) | Returns an index of the specified DataLabel in the collection. |
| [isVisible](isvisible)() | False means that data label is not visible by default (and so all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Read-only boolean. If data label is visible by default you can make it hidden by default with Hide() method. But if data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state. |
| [iterator](iterator)() | Returns an enumerator that iterates through the collection. |
| [iteratorJava](iteratorjava)() | Returns a java iterator for the entire collection. |
