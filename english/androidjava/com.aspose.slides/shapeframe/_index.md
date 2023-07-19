---
title: ShapeFrame
second_title: Aspose.Slides for Android via Java API Reference
description: Represents shape frames properties.
type: docs
weight: 498
url: /androidjava/com.aspose.slides/shapeframe/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Represents shape frame's properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Creates new shape frame's properties. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | Returns the X coordinate of the upper-left corner of a frame. |
| [getY()](#getY--) | Returns the Y coordinate of the upper-left corner of a frame. |
| [getWidth()](#getWidth--) | Returns the width of a frame. |
| [getHeight()](#getHeight--) | Returns the height of a frame. |
| [getRotation()](#getRotation--) | Returns the number of degrees a frame is rotated around the z-axis. |
| [getCenterX()](#getCenterX--) | Returns the X coordinate of a frame's center. |
| [getCenterY()](#getCenterY--) | Returns the Y coordinate of a frame's center. |
| [getFlipH()](#getFlipH--) | Determines whether a frame is flipped horizontally. |
| [getFlipV()](#getFlipV--) | Determines whether a frame is flipped vertically. |
| [getRectangle()](#getRectangle--) | Returns the coordinates of a frame. |
| [deepClone()](#deepClone--) | Clones |
| [cloneT()](#cloneT--) | Clones. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified object. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Returns a value indicating whether this instance is equal to a specified object. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


Creates new shape frame's properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a frame. |
| y | float | Y coordinate of a frame. |
| width | float | Width of a frame. |
| height | float | Height of a frame. |
| flipH | byte | True if a frame flipped horizontally. |
| flipV | byte | True if a frame flipped vertivally. |
| rotationAngle | float | Number of degrees a frame is rotated. |

### getX() {#getX--}
```
public final float getX()
```


Returns the X coordinate of the upper-left corner of a frame. Read-only float.

**Returns:**
float
### getY() {#getY--}
```
public final float getY()
```


Returns the Y coordinate of the upper-left corner of a frame. Read-only float.

**Returns:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Returns the width of a frame. Read-only float.

**Returns:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returns the height of a frame. Read-only float.

**Returns:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Returns the number of degrees a frame is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read-only float.

**Returns:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Returns the X coordinate of a frame's center. Read-only float.

**Returns:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Returns the Y coordinate of a frame's center. Read-only float.

**Returns:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


Determines whether a frame is flipped horizontally. Read-only [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


Determines whether a frame is flipped vertically. Read-only [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


Returns the coordinates of a frame. Read-only android.graphics.RectF.

**Returns:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clones

**Returns:**
java.lang.Object - Cloned shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


Clones.

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Cloned shape frame.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with this instance. |

**Returns:**
boolean - **true** if obj is a ShapeFrame that has the same value as this instance; otherwise, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


Returns a value indicating whether this instance is equal to a specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | The ShapeFRameEx to compare with this instance. |

**Returns:**
boolean - **true** if value is a ShapeFrame that has the same value as this instance; otherwise, **false**.
