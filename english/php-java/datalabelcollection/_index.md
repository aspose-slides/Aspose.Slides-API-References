---
title: DataLabelCollection
type: docs
weight: 0
url: /php-java/datalabelcollection/
---

# DataLabelCollection class

 Represents a series labels.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getChart](/php-java/datalabelcollection/getchart/)() | IChart | Returns the parent chart. Read-only IChart. |
| [getCount](/php-java/datalabelcollection/getcount/)() | int | Gets the number of all data labels in the collection. Read-only int. |
| [getCountOfVisibleDataLabels](/php-java/datalabelcollection/getcountofvisibledatalabels/)() | int | Gets the number of visible data labels in the collection. Read-only int. |
| [getDefaultDataLabelFormat](/php-java/datalabelcollection/getdefaultdatalabelformat/)() | IDataLabelFormat | Gets the default data label format. Read-only IDataLabelFormat. |
| [getParentSeries](/php-java/datalabelcollection/getparentseries/)() | IChartSeries | Gets the parent series. Read-only IChartSeries. |
| [getPresentation](/php-java/datalabelcollection/getpresentation/)() | IPresentation | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getSlide](/php-java/datalabelcollection/getslide/)() | IBaseSlide | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [get_Item](/php-java/datalabelcollection/get_item/)(int) | IDataLabel | Gets the data label for the data point with the specified index. Alternate way to access data label is: - series.getDataPoints().get_Item(i).getLabel() - manage label properties. |
| [hide](/php-java/datalabelcollection/hide/)() | void | Make data label hidden by default by setting all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. IsVisible will be false after this. If data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state. |
| [indexOf](/php-java/datalabelcollection/indexof/)(IDataLabel) | int | Returns an index of the specified DataLabel in the collection. |
| [isVisible](/php-java/datalabelcollection/isvisible/)() | boolean | False means that data label is not visible by default (and so all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Read-only boolean. If data label is visible by default you can make it hidden by default with Hide() method. But if data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state. |
| [iterator](/php-java/datalabelcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/datalabelcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
