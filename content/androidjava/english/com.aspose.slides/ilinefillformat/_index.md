---
title: ILineFillFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties for lines filling.
type: docs
url: /com.aspose.slides/ilinefillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

Represents properties for lines filling.
## Methods

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Returns or sets the fill type. |
| [setFillType(byte value)](#setFillType-byte-) | Returns or sets the fill type. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the color of a solid fill. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with a shape. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Determines whether the fill should be rotated with a shape. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returns or sets the fill type. Read/write [FillType](../../com.aspose.slides/filltype).

**Returns:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```


Returns or sets the fill type. Read/write [FillType](../../com.aspose.slides/filltype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```


Returns the color of a solid fill. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

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
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


Determines whether the fill should be rotated with a shape. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


Determines whether the fill should be rotated with a shape. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

