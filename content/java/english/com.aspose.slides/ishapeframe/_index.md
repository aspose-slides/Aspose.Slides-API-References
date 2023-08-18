---
title: IShapeFrame
second_title: Aspose.Slides for Java API Reference
description: Represents shape frames properties.
type: docs
url: /com.aspose.slides/ishapeframe/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Represents shape frame's properties.
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
### getX() {#getX--}
```
public abstract float getX()
```


Returns the X coordinate of the upper-left corner of a frame. Read-only float.

**Returns:**
float
### getY() {#getY--}
```
public abstract float getY()
```


Returns the Y coordinate of the upper-left corner of a frame. Read-only float.

**Returns:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Returns the width of a frame. Read-only float.

**Returns:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Returns the height of a frame. Read-only float.

**Returns:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Returns the number of degrees a frame is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read-only float.

**Returns:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


Returns the X coordinate of a frame's center. Read-only float.

**Returns:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


Returns the Y coordinate of a frame's center. Read-only float.

**Returns:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


Determines whether a frame is flipped horizontally. Read-only [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


Determines whether a frame is flipped vertically. Read-only [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```


Returns the coordinates of a frame. Read-only java.awt.geom.Rectangle2D.Float.

**Returns:**
java.awt.geom.Rectangle2D.Float
