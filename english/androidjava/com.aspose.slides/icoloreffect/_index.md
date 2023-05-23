---
title: IColorEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a color effect for an animation behavior.
type: docs
weight: 713
url: /androidjava/com.aspose.slides/icoloreffect/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Represents a color effect for an animation behavior.
## Methods

| Method | Description |
| --- | --- |
| [getFrom()](#getFrom--) | This value is used to specify the starting color of behavior. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | This value is used to specify the starting color of behavior. |
| [getTo()](#getTo--) | Describes resulting color for the animation color change. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Describes resulting color for the animation color change. |
| [getBy()](#getBy--) | Describes the relative offset value for the color animation. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Describes the relative offset value for the color animation. |
| [getColorSpace()](#getColorSpace--) | Represent color space of behavior. |
| [setColorSpace(int value)](#setColorSpace-int-) | Represent color space of behavior. |
| [getDirection()](#getDirection--) | Specifies which direction to cycle the hue around the color wheel. |
| [setDirection(int value)](#setDirection-int-) | Specifies which direction to cycle the hue around the color wheel. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```


This value is used to specify the starting color of behavior. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```


This value is used to specify the starting color of behavior. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```


Describes resulting color for the animation color change. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```


Describes resulting color for the animation color change. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```


Describes the relative offset value for the color animation. Read/write [IColorOffset](../../com.aspose.slides/icoloroffset).

**Returns:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```


Describes the relative offset value for the color animation. Read/write [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```


Represent color space of behavior. Read/write [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```


Represent color space of behavior. Read/write [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Specifies which direction to cycle the hue around the color wheel. Read/write [ColorDirection](../../com.aspose.slides/colordirection).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Specifies which direction to cycle the hue around the color wheel. Read/write [ColorDirection](../../com.aspose.slides/colordirection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

