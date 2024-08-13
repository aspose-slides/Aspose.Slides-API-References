---
title: PictureFillFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a picture fill style.
type: docs
url: /com.aspose.slides/picturefillformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Represents a picture fill style.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Returns or sets the dpi which is used to fill a picture. |
| [setDpi(int value)](#setDpi-int-) | Returns or sets the dpi which is used to fill a picture. |
| [getPictureFillMode()](#getPictureFillMode--) | Returns or sets the picture fill mode. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Returns or sets the picture fill mode. |
| [getPicture()](#getPicture--) | Returns the picture. |
| [getCropLeft()](#getCropLeft--) | Returns or sets the number of percents of real image width that are cropped off the left of the picture. |
| [setCropLeft(float value)](#setCropLeft-float-) | Returns or sets the number of percents of real image width that are cropped off the left of the picture. |
| [getCropTop()](#getCropTop--) | Returns or sets the number of percents of real image height that are cropped off the top of the picture. |
| [setCropTop(float value)](#setCropTop-float-) | Returns or sets the number of percents of real image height that are cropped off the top of the picture. |
| [getCropRight()](#getCropRight--) | Returns or sets the number of percents of real image width that are cropped off the right of the picture. |
| [setCropRight(float value)](#setCropRight-float-) | Returns or sets the number of percents of real image width that are cropped off the right of the picture. |
| [getCropBottom()](#getCropBottom--) | Returns or sets the number of percents of real image height that are cropped off the bottom of the picture. |
| [setCropBottom(float value)](#setCropBottom-float-) | Returns or sets the number of percents of real image height that are cropped off the bottom of the picture. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Delete cropped areas of the fill Picture. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. |
| [getTileOffsetX()](#getTileOffsetX--) | Returns or sets the horizontal offset of the texture from the shape's origin in points. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Returns or sets the horizontal offset of the texture from the shape's origin in points. |
| [getTileOffsetY()](#getTileOffsetY--) | Returns or sets the vertical offset of the texture from the shape's origin in points. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Returns or sets the vertical offset of the texture from the shape's origin in points. |
| [getTileScaleX()](#getTileScaleX--) | Returns or sets the horizontal scale for the texture fill as a percentage. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Returns or sets the horizontal scale for the texture fill as a percentage. |
| [getTileScaleY()](#getTileScaleY--) | Returns or sets the vertical scale for the texture fill as a percentage. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Returns or sets the vertical scale for the texture fill as a percentage. |
| [getTileAlignment()](#getTileAlignment--) | Returns or sets how the texture is aligned within the shape. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Returns or sets how the texture is aligned within the shape. |
| [getTileFlip()](#getTileFlip--) | Flips the texture tile around its horizontal, vertical or both axis. |
| [setTileFlip(int value)](#setTileFlip-int-) | Flips the texture tile around its horizontal, vertical or both axis. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getDpi() {#getDpi--}
```
public final int getDpi()
```


Returns or sets the dpi which is used to fill a picture. Read/write  int .

**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Returns or sets the dpi which is used to fill a picture. Read/write  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```


Returns or sets the picture fill mode. Read/write [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Returns:**
int
### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```


Returns or sets the picture fill mode. Read/write [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Returns the picture. Read-only [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Returns:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```


Returns or sets the number of percents of real image width that are cropped off the left of the picture. Read/write  float .

**Returns:**
float
### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```


Returns or sets the number of percents of real image width that are cropped off the left of the picture. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```


Returns or sets the number of percents of real image height that are cropped off the top of the picture. Read/write  float .

**Returns:**
float
### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```


Returns or sets the number of percents of real image height that are cropped off the top of the picture. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```


Returns or sets the number of percents of real image width that are cropped off the right of the picture. Read/write  float .

**Returns:**
float
### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```


Returns or sets the number of percents of real image width that are cropped off the right of the picture. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```


Returns or sets the number of percents of real image height that are cropped off the bottom of the picture. Read/write  float .

**Returns:**
float
### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```


Returns or sets the number of percents of real image height that are cropped off the bottom of the picture. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```


Delete cropped areas of the fill Picture.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Deletes cropped areas of the PictureFrame image
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Cropped image or origin image if cropping is not necessary.

--------------------

This method converts WMF/EMF metafiles to raster PNG image while cropping.
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```


Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```


Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public final float getStretchOffsetTop()
```


Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public final void setStretchOffsetTop(float value)
```


Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public final float getStretchOffsetRight()
```


Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public final void setStretchOffsetRight(float value)
```


Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public final float getStretchOffsetBottom()
```


Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```


Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public final float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public final void setTileScaleX(float value)
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public final float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public final void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public final byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public final void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write  TileFlip (\#getTileFlip.getTileFlip/\#setTileFlip(int).setTileFlip(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write  TileFlip (\#getTileFlip.getTileFlip/\#setTileFlip(int).setTileFlip(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

