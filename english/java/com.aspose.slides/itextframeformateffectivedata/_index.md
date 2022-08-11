---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description:  Immutable object which contains effective text frame formatting properties.
type: docs
weight: 1066
url: /java/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Immutable object which contains effective text frame formatting properties.

--------------------

This interface is used together with the [ITextFrameFormat](../../com.aspose.slides/itextframeformat) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returns effective text's style. |
| [getMarginLeft()](#getMarginLeft--) | Returns the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | Returns if text is wrapped at TextFrame's margins. |
| [getAnchoringType()](#getAnchoringType--) | Returns vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | Returns if text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Returns text orientation. |
| [getAutofitType()](#getAutofitType--) | Returns text autofit mode. |
| [getColumnCount()](#getColumnCount--) | Specifies the number of columns of text in the bounding rectangle. |
| [getColumnSpacing()](#getColumnSpacing--) | Specifies the space between text columns in the text area (in points). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Returns effective text's style. Read-only [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Returns the left margin (points) in a TextFrame. Read-only double.

**Returns:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Returns the right margin (points) in a TextFrame. Read-only double.

**Returns:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Returns the top margin (points) in a TextFrame. Read-only double.

**Returns:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Returns the bottom margin (points) in a TextFrame. Read-only double.

**Returns:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Returns if text is wrapped at TextFrame's margins. Read-only boolean.

**Returns:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Returns vertical anchor text in a TextFrame. Read-only [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returns:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Returns if text should be centered in box horizontally. Read-only boolean.

**Returns:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Returns text orientation. Read-only [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returns:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Returns text autofit mode. Read-only [TextAutofitType](../../com.aspose.slides/textautofittype).

**Returns:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Specifies the number of columns of text in the bounding rectangle. Read-only int.

**Returns:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Specifies the space between text columns in the text area (in points). Read-only float.

**Returns:**
float
