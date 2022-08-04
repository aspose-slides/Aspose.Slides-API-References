---
title: Marker
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents marker of a chert.
type: docs
weight: 292
url: /java/com.aspose.slides/marker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMarker](../../com.aspose.slides/imarker), com.aspose.slides.IDOMObject
```
public class Marker implements IMarker, IDOMObject
```

Represents marker of a chert.
## Constructors

| Constructor | Description |
| --- | --- |
| [Marker(IDOMObject parentImmediate, ChartSeries parentSeries)](#Marker-com.aspose.slides.IDOMObject-com.aspose.slides.ChartSeries-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSymbol()](#getSymbol--) | Represents the marker style in a line chart, scatter chart, or radar chart. |
| [setSymbol(int value)](#setSymbol-int-) | Represents the marker style in a line chart, scatter chart, or radar chart. |
| [getFormat()](#getFormat--) | Gets or sets the marker fill. |
| [getSize()](#getSize--) | Represents the marker size in a line chart, scatter chart, or radar chart. |
| [setSize(int value)](#setSize-int-) | Represents the marker size in a line chart, scatter chart, or radar chart. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Marker(IDOMObject parentImmediate, ChartSeries parentSeries) {#Marker-com.aspose.slides.IDOMObject-com.aspose.slides.ChartSeries-}
```
 Marker(IDOMObject parentImmediate, ChartSeries parentSeries)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| parentSeries | [ChartSeries](../../com.aspose.slides/chartseries) |  |

### getSymbol() {#getSymbol--}
```
public final int getSymbol()
```


Represents the marker style in a line chart, scatter chart, or radar chart. Read/write [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Returns:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public final void setSymbol(int value)
```


Represents the marker style in a line chart, scatter chart, or radar chart. Read/write [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Gets or sets the marker fill. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public final int getSize()
```


Represents the marker size in a line chart, scatter chart, or radar chart. Read/write int.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Represents the marker size in a line chart, scatter chart, or radar chart. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
