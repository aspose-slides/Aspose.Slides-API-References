---
title: IDataLabelCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a series labels.
type: docs
weight: 741
url: /androidjava/com.aspose.slides/idatalabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Represents a series labels.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the data label for the data point with the specified index. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Returns default format of all data labels in the collection. |
| [getLeaderLinesColor()](#getLeaderLinesColor--) | Gets or sets the color of all leader lines in the collection. |
| [setLeaderLinesColor(Integer value)](#setLeaderLinesColor-java.lang.Integer-) | Gets or sets the color of all leader lines in the collection. |
| [isVisible()](#isVisible--) | False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). |
| [hide()](#hide--) | Make data label hidden by default by setting all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Gets the number of visible data labels in the collection. |
| [getCount()](#getCount--) | Gets the number of all data labels in the collection. |
| [getParentSeries()](#getParentSeries--) | Returns parent chart series. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returns an index of the specified DataLabel in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Gets the data label for the data point with the specified index.

--------------------

Alternate way to access data label is: - getSeries().getDataPoints().get\_Item(i).getLabel() - manage label properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Returns default format of all data labels in the collection. Read-only [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesColor() {#getLeaderLinesColor--}
```
public abstract Integer getLeaderLinesColor()
```


Gets or sets the color of all leader lines in the collection. Read/write java.lang.Integer.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
> 
>      labels.setLeaderLinesColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.Integer
### setLeaderLinesColor(Integer value) {#setLeaderLinesColor-java.lang.Integer-}
```
public abstract void setLeaderLinesColor(Integer value)
```


Gets or sets the color of all leader lines in the collection. Read/write java.lang.Integer.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
> 
>      labels.setLeaderLinesColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Read-only  boolean .

--------------------

If data label is visible by default you can make it hidden by default with Hide() method. But if data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state.

**Returns:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Make data label hidden by default by setting all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. IsVisible will be false after this.

--------------------

If data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Gets the number of visible data labels in the collection. Read-only  int .

**Returns:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of all data labels in the collection. Read-only  int .

**Returns:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Returns parent chart series. Read-only [IChartSeries](../../com.aspose.slides/ichartseries).

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Returns an index of the specified DataLabel in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel to find. |

**Returns:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
