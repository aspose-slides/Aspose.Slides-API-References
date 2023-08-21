---
title: ILineFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective line formatting properties.
type: docs
url: /com.aspose.slides/ilineformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Immutable object which contains effective line formatting properties.

--------------------

This interface is used together with the [ILineFormat](../../com.aspose.slides/ilineformat) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns the fill format of a line. |
| [getSketchFormat()](#getSketchFormat--) | Returns the sketch format of a line. |
| [getWidth()](#getWidth--) | Returns the width of a line. |
| [getDashStyle()](#getDashStyle--) | Returns the line dash style. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returns the custom dash pattern. |
| [getCapStyle()](#getCapStyle--) | Returns the line cap style. |
| [getStyle()](#getStyle--) | Returns the line style. |
| [getAlignment()](#getAlignment--) | Returns the line alignment. |
| [getJoinStyle()](#getJoinStyle--) | Returns the lines join style. |
| [getMiterLimit()](#getMiterLimit--) | Returns the miter limit of a line. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returns the arrowhead style at the beginning of a line. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returns the arrowhead style at the end of a line. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returns the arrowhead width at the beginning of a line. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returns the arrowhead width at the end of a line. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returns the arrowhead length at the beginning of a line. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returns the arrowhead length at the end of a line. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Determines whether the two ILineFormatEffectiveData instances are equal. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Returns the fill format of a line. Read-only [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Returns:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Returns the sketch format of a line. Read-only [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Returns:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Returns the width of a line. Read-only double.

**Returns:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Returns the line dash style. Read-only [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Returns:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Returns the custom dash pattern. Read-only float[].

**Returns:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Returns the line cap style. Read-only [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Returns:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Returns the line style. Read-only [LineStyle](../../com.aspose.slides/linestyle).

**Returns:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Returns the line alignment. Read-only [LineAlignment](../../com.aspose.slides/linealignment).

**Returns:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Returns the lines join style. Read-only [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Returns:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Returns the miter limit of a line. Read-only float.

**Returns:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Returns the arrowhead style at the beginning of a line. Read-only [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returns:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Returns the arrowhead style at the end of a line. Read-only [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returns:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Returns the arrowhead width at the beginning of a line. Read-only [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returns:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Returns the arrowhead width at the end of a line. Read-only [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returns:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Returns the arrowhead length at the beginning of a line. Read-only [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returns:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Returns the arrowhead length at the end of a line. Read-only [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returns:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Determines whether the two ILineFormatEffectiveData instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | The ILineFormatEffectiveData to compare with the current ILineFormatEffectiveData. |

**Returns:**
boolean - **true** if the specified ILineFormatEffectiveData is equal to the current ILineFormatEffectiveData; otherwise, **false**.
