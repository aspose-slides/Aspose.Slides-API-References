---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Represents a size of slide.
type: docs
weight: 1031
url: /java/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Represents a size of slide.
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Returns or sets the size in points. |
| [getType()](#getType--) | Returns or sets the type of slide size. |
| [getOrientation()](#getOrientation--) | Returns or sets the slide orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Returns or sets the slide orientation. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Sets the type of slide size and scales content using scale type. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Sets the size in points and scales content using scale type. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Returns or sets the size in points. Read/write java.awt.geom.Dimension2D.

--------------------

Assigning any value will reset (\#getType.getType) property to [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) and set ([getOrientation](../../com.aspose.slides/islidesize\#getOrientation)/[setOrientation(int)](../../com.aspose.slides/islidesize\#setOrientation-int-)).

**Returns:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


Returns or sets the type of slide size. Read/write [SlideSizeType](../../com.aspose.slides/slidesizetype).

--------------------

Assigning any value except [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) will change ([getSize](../../com.aspose.slides/islidesize\#getSize)) accordingly, but will keep ([getOrientation](../../com.aspose.slides/islidesize\#getOrientation)/[setOrientation(int)](../../com.aspose.slides/islidesize\#setOrientation-int-)) intact.

**Returns:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Returns or sets the slide orientation. Read/write [SlideOrientation](../../com.aspose.slides/slideorientation).

--------------------

Changing this value will swap slide's dimensions.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Returns or sets the slide orientation. Read/write [SlideOrientation](../../com.aspose.slides/slideorientation).

--------------------

Changing this value will swap slide's dimensions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Sets the type of slide size and scales content using scale type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Slide size type. |
| scaleType | int | Scale type of slide content.

--------------------

Assigning any value except [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) will change ([getSize](../../com.aspose.slides/islidesize\#getSize)) accordingly, but will keep ([getOrientation](../../com.aspose.slides/islidesize\#getOrientation)/[setOrientation(int)](../../com.aspose.slides/islidesize\#setOrientation-int-)) intact. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Sets the size in points and scales content using scale type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Width. |
| height | float | Height. |
| scaleType | int | Scale type of slide content.

--------------------

Assigning any value will reset (\#getType.getType) property to [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) and set ([getOrientation](../../com.aspose.slides/islidesize\#getOrientation)/[setOrientation(int)](../../com.aspose.slides/islidesize\#setOrientation-int-)). |

