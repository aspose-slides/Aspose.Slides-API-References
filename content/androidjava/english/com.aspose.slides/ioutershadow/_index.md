---
title: IOuterShadow
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an Outer Shadow effect.
type: docs
url: /com.aspose.slides/ioutershadow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Represents an Outer Shadow effect.
## Methods

| Method | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Blur radius, in points. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Blur radius, in points. |
| [getDirection()](#getDirection--) | Direction of the shadow, in degrees. |
| [setDirection(float value)](#setDirection-float-) | Direction of the shadow, in degrees. |
| [getDistance()](#getDistance--) | Distance of the shadow from the object, in points. |
| [setDistance(double value)](#setDistance-double-) | Distance of the shadow from the object, in points. |
| [getShadowColor()](#getShadowColor--) | Color of the shadow. |
| [getRectangleAlign()](#getRectangleAlign--) | Rectangle alignment. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Rectangle alignment. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Horizontal skew angle, in degrees. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Horizontal skew angle, in degrees. |
| [getSkewVertical()](#getSkewVertical--) | Vertical skew angle, in degrees. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Vertical skew angle, in degrees. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Indicates whether the shadow rotates together with the shape. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Indicates whether the shadow rotates together with the shape. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Horizontal scaling factor, in percent of the original size. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Horizontal scaling factor, in percent of the original size. |
| [getScaleVertical()](#getScaleVertical--) | Vertical scaling factor, in percent of the original size. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Vertical scaling factor, in percent of the original size. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


Blur radius, in points. Default value - 0 pt. Read/write double.

**Returns:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


Blur radius, in points. Default value - 0 pt. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Direction of the shadow, in degrees. Default value - 0 ° (left-to-right). Read/write float.

**Returns:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Direction of the shadow, in degrees. Default value - 0 ° (left-to-right). Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Distance of the shadow from the object, in points. Default value - 0 pt. Read/write double.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Distance of the shadow from the object, in points. Default value - 0 pt. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Color of the shadow. Default value - automatic black (theme-dependent). Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


Rectangle alignment. Default value - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Returns:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```


Rectangle alignment. Default value - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


Horizontal skew angle, in degrees. Default value - 0 °. Read/write double.

**Returns:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```


Horizontal skew angle, in degrees. Default value - 0 °. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


Vertical skew angle, in degrees. Default value - 0 °. Read/write double.

**Returns:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```


Vertical skew angle, in degrees. Default value - 0 °. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


Indicates whether the shadow rotates together with the shape. Default value - true. Read/write boolean.

**Returns:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```


Indicates whether the shadow rotates together with the shape. Default value - true. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


Horizontal scaling factor, in percent of the original size. Negative scaling causes a flip. Default value - 100 %. Read/write double.

**Returns:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```


Horizontal scaling factor, in percent of the original size. Negative scaling causes a flip. Default value - 100 %. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


Vertical scaling factor, in percent of the original size. Negative scaling causes a flip. Default value - 100 %. Read/write double.

**Returns:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```


Vertical scaling factor, in percent of the original size. Negative scaling causes a flip. Default value - 100 %. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

