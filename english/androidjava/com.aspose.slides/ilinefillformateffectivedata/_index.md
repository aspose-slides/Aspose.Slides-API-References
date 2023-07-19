---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective line filling properties.
type: docs
weight: 862
url: /androidjava/com.aspose.slides/ilinefillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Immutable object which contains effective line filling properties.

--------------------

This interface is used as a part of [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Returns the fill type. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the color of a solid fill. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with a shape. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returns the fill type. Read-only [FillType](../../com.aspose.slides/filltype).

**Returns:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Returns the color of a solid fill. Read-only java.lang.Integer.

**Returns:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Returns the gradient fill format. Read-only [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Returns:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Returns the pattern fill format. Read-only [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Returns:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Determines whether the fill should be rotated with a shape. Read-only boolean.

**Returns:**
boolean
