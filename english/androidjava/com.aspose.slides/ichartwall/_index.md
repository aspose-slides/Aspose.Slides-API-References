---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Represents walls on 3d charts.
type: docs
weight: 706
url: /androidjava/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Represents walls on 3d charts.
## Methods

| Method | Description |
| --- | --- |
| [getThickness()](#getThickness--) | Returns or sets the walls thickness as a percentage of the largest dimension of the plot volume. |
| [setThickness(int value)](#setThickness-int-) | Returns or sets the walls thickness as a percentage of the largest dimension of the plot volume. |
| [getFormat()](#getFormat--) | Returns the wall fill, line, effect, 3d styles. |
| [getPictureType()](#getPictureType--) | Return or sets the picture type. |
| [setPictureType(int value)](#setPictureType-int-) | Return or sets the picture type. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


Returns or sets the walls thickness as a percentage of the largest dimension of the plot volume. Read/write int.

**Returns:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


Returns or sets the walls thickness as a percentage of the largest dimension of the plot volume. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Returns the wall fill, line, effect, 3d styles. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


Return or sets the picture type. Read/write [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Returns:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```


Return or sets the picture type. Read/write [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

