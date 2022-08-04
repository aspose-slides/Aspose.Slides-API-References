---
title: IFillFormat
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a fill formatting options.
type: docs
weight: 768
url: /java/com.aspose.slides/ifillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

Represents a fill formatting options.
## Methods

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Returns or sets the type of filling. |
| [setFillType(byte value)](#setFillType-byte-) | Returns or sets the type of filling. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the fill color. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returns the picture fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with shape. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determines whether the fill should be rotated with shape. |
| [getEffective()](#getEffective--) | Gets effective fill formatting data with the inheritance applied. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returns or sets the type of filling. Read/write [FillType](../../com.aspose.slides/filltype).

**Returns:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Returns or sets the type of filling. Read/write [FillType](../../com.aspose.slides/filltype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Returns the fill color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


Returns the gradient fill format. Read-only [IGradientFormat](../../com.aspose.slides/igradientformat).

**Returns:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


Returns the pattern fill format. Read-only [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Returns:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```


Returns the picture fill format. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Determines whether the fill should be rotated with shape. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Determines whether the fill should be rotated with shape. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```


Gets effective fill formatting data with the inheritance applied.

**Returns:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../com.aspose.slides/ifillformateffectivedata).
