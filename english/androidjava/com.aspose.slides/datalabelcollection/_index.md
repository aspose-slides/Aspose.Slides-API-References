---
title: DataLabelCollection
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents a series labels.
type: docs
weight: 148
url: /androidjava/com.aspose.slides/datalabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Represents a series labels.
## Methods

| Method | Description |
| --- | --- |
| [getChart()](#getChart--) | Returns the parent chart. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [isVisible()](#isVisible--) | False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). |
| [hide()](#hide--) | Make data label hidden by default by setting all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Gets the number of visible data labels in the collection. |
| [getCount()](#getCount--) | Gets the number of all data labels in the collection. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Gets the default data label format. |
| [getParentSeries()](#getParentSeries--) | Gets the parent series. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returns an index of the specified DataLabel in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the data label for the data point with the specified index. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returns the parent chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Read-only boolean.

--------------------

If data label is visible by default you can make it hidden by default with Hide() method. But if data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state.

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Make data label hidden by default by setting all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. IsVisible will be false after this.

--------------------

If data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Gets the number of visible data labels in the collection. Read-only int.

**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of all data labels in the collection. Read-only int.

**Returns:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Gets the default data label format. Read-only [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```


Gets the parent series. Read-only [IChartSeries](../../com.aspose.slides/ichartseries).

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Returns an index of the specified DataLabel in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel to find. |

**Returns:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Gets the data label for the data point with the specified index.

--------------------

Alternate way to access data label is: - series.getDataPoints().get\_Item(i).getLabel() - manage label properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
