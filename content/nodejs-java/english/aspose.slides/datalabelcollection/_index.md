---
title: DataLabelCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/datalabelcollection/
---

## DataLabelCollection class

 Represents a series labels.
 
### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Returns the parent chart. Read-only IChart. |

 **Returns:**
[Chart](../chart)


---


### getCount {#getCount}

| Name | Description |
| --- | --- |
| getCount () | Gets the number of all data labels in the collection. Read-only int. |

 **Returns:**
int


---


### getCountOfVisibleDataLabels {#getCountOfVisibleDataLabels}

| Name | Description |
| --- | --- |
| getCountOfVisibleDataLabels () | Gets the number of visible data labels in the collection. Read-only int. |

 **Returns:**
int


---


### getDefaultDataLabelFormat {#getDefaultDataLabelFormat}

| Name | Description |
| --- | --- |
| getDefaultDataLabelFormat () | Gets the default data label format. Read-only IDataLabelFormat. |

 **Returns:**
[DataLabelFormat](../datalabelformat)


---


### getLeaderLinesFormat {#getLeaderLinesFormat}

| Name | Description |
| --- | --- |
| getLeaderLinesFormat () | Represents data labels leader lines format. Read-only IChartLinesFormat. |

 **Returns:**
[ChartLinesFormat](../chartlinesformat)


---


### getParentSeries {#getParentSeries}

| Name | Description |
| --- | --- |
| getParentSeries () | Gets the parent series. Read-only IChartSeries. |

 **Returns:**
[ChartSeries](../chartseries)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

 **Returns:**
[BaseSlide](../baseslide), [MasterSlide](../masterslide), [MasterNotesSlide](../masternotesslide), [Slide](../slide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [NotesSlide](../notesslide)


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the data label for the data point with the specified index. Alternate way to access data label is: - series.getDataPoints().get_Item(i).getLabel() - manage label properties. |

 **Returns:**
[DataLabel](../datalabel)


---


### hide {#hide}

| Name | Description |
| --- | --- |
| hide () | Make data label hidden by default by setting all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. IsVisible will be false after this. If data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state. |


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([DataLabel](../datalabel)) | Returns an index of the specified DataLabel in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [DataLabel](../datalabel) | DataLabel to find. |

 **Returns:**
int


---


### isVisible {#isVisible}

| Name | Description |
| --- | --- |
| isVisible () | False means that data label is not visible by default (and so all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Read-only boolean. If data label is visible by default you can make it hidden by default with Hide() function. But if data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state. |

 **Returns:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Returns:**



---


