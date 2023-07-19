---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective fill formatting properties.
type: docs
weight: 780
url: /androidjava/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

Immutable object which contains effective fill formatting properties.

--------------------

This interface is used together with the [IFillFormat](../../com.aspose.slides/ifillformat) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Returns the type of filling. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the fill color. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returns the picture fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with shape. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returns the type of filling. Read-only [FillType](../../com.aspose.slides/filltype).

**Returns:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Returns the fill color. Read-only java.lang.Integer.

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
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Returns the picture fill format. Read-only [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**Returns:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Determines whether the fill should be rotated with shape. Read-only boolean.

**Returns:**
boolean
