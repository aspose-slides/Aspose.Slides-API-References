---
title: OuterShadow
second_title: Aspose.Slides for Java API Reference
description: Represents an Outer Shadow effect.
type: docs
url: /com.aspose.slides/outershadow/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
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
| [getEffective()](#getEffective--) | Gets effective Outer Shadow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [OuterShadow](../../com.aspose.slides/outershadow) is equal to the current [OuterShadow](../../com.aspose.slides/outershadow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


Blur radius, in points. Default value - 0 pt. Read/write double.

**Returns:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


Blur radius, in points. Default value - 0 pt. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```


Direction of the shadow, in degrees. Default value - 0 ° (left-to-right). Read/write float.

**Returns:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Direction of the shadow, in degrees. Default value - 0 ° (left-to-right). Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Distance of the shadow from the object, in points. Default value - 0 pt. Read/write double.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Distance of the shadow from the object, in points. Default value - 0 pt. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Color of the shadow. Default value - automatic black (theme-dependent). Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```


Rectangle alignment. Default value - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Returns:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```


Rectangle alignment. Default value - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```


Horizontal skew angle, in degrees. Default value - 0 °. Read/write double.

**Returns:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```


Horizontal skew angle, in degrees. Default value - 0 °. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```


Vertical skew angle, in degrees. Default value - 0 °. Read/write double.

**Returns:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```


Vertical skew angle, in degrees. Default value - 0 °. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```


Indicates whether the shadow rotates together with the shape. Default value - true. Read/write boolean.

**Returns:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```


Indicates whether the shadow rotates together with the shape. Default value - true. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```


Horizontal scaling factor, in percent of the original size. Negative scaling causes a flip. Default value - 100 %. Read/write double.

**Returns:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```


Horizontal scaling factor, in percent of the original size. Negative scaling causes a flip. Default value - 100 %. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```


Vertical scaling factor, in percent of the original size. Negative scaling causes a flip. Default value - 100 %. Read/write double.

**Returns:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```


Vertical scaling factor, in percent of the original size. Negative scaling causes a flip. Default value - 100 %. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```


Gets effective Outer Shadow effect data with the inheritance applied.

**Returns:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Returns parent IPresentationComponent. Read-only [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [OuterShadow](../../com.aspose.slides/outershadow) is equal to the current [OuterShadow](../../com.aspose.slides/outershadow).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [OuterShadow](../../com.aspose.slides/outershadow) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
