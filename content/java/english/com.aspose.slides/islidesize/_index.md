---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Represents the size and orientation of a slide.
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Gets the slide dimensions in points. |
| [getType()](#getType--) | Gets the slide size type. |
| [getOrientation()](#getOrientation--) | Gets or sets the slide orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the slide orientation. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Sets the slide size by type and scales existing content. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Sets the slide dimensions explicitly and scales existing content. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Gets the slide dimensions in points.

--------------------

Assigning a new value resets the \#getType.getType property to [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) and sets the \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Returns:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


Gets the slide size type.

--------------------

Assigning any value other than [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) adjusts the \#getSize.getSize according to the predefined dimensions, while retaining the current \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Returns:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Gets or sets the slide orientation.

--------------------

Changing this value swaps the slide's width and height.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Gets or sets the slide orientation.

--------------------

Changing this value swaps the slide's width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Sets the slide size by type and scales existing content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The predefined slide size to apply. |
| scaleType | int | The content scaling mode to use.

--------------------

Assigning any value other than [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) adjusts the \#getSize.getSize based on the selected type, while preserving \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Sets the slide dimensions explicitly and scales existing content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | The new slide width, in points. |
| height | float | The new slide height, in points. |
| scaleType | int | The content scaling mode to use.

--------------------

This resets the \#getType.getType property to [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) and sets the \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

