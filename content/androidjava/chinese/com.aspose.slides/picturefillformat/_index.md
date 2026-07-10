---
title: PictureFillFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种图片填充样式。
type: docs
url: /zh/com.aspose.slides/picturefillformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

表示一种图片填充样式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | 返回或设置用于填充图片的 dpi。 |
| [setDpi(int value)](#setDpi-int-) | 返回或设置用于填充图片的 dpi。 |
| [getPictureFillMode()](#getPictureFillMode--) | 返回或设置图片填充模式。 |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 返回或设置图片填充模式。 |
| [getPicture()](#getPicture--) | 返回图片。 |
| [getCropLeft()](#getCropLeft--) | 返回或设置图片左侧裁剪掉的实际图像宽度的百分比。 |
| [setCropLeft(float value)](#setCropLeft-float-) | 返回或设置图片左侧裁剪掉的实际图像宽度的百分比。 |
| [getCropTop()](#getCropTop--) | 返回或设置图片顶部裁剪掉的实际图像高度的百分比。 |
| [setCropTop(float value)](#setCropTop-float-) | 返回或设置图片顶部裁剪掉的实际图像高度的百分比。 |
| [getCropRight()](#getCropRight--) | 返回或设置图片右侧裁剪掉的实际图像宽度的百分比。 |
| [setCropRight(float value)](#setCropRight-float-) | 返回或设置图片右侧裁剪掉的实际图像宽度的百分比。 |
| [getCropBottom()](#getCropBottom--) | 返回或设置图片底部裁剪掉的实际图像高度的百分比。 |
| [setCropBottom(float value)](#setCropBottom-float-) | 返回或设置图片底部裁剪掉的实际图像高度的百分比。 |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 删除填充图片的裁剪区域。 |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | 通过根据形状大小和指定分辨率压缩图像来减小其尺寸。 |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | 通过根据形状大小和指定分辨率压缩图像来减小其尺寸。 |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | 返回或设置填充矩形左边缘，该边缘由相对于形状边界框左边缘的百分比偏移定义。 |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | 返回或设置填充矩形左边缘，该边缘由相对于形状边界框左边缘的百分比偏移定义。 |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | 返回或设置填充矩形上边缘，该边缘由相对于形状边界框上边缘的百分比偏移定义。 |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | 返回或设置填充矩形上边缘，该边缘由相对于形状边界框上边缘的百分比偏移定义。 |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | 返回或设置填充矩形右边缘，该边缘由相对于形状边界框右边缘的百分比偏移定义。 |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | 返回或设置填充矩形右边缘，该边缘由相对于形状边界框右边缘的百分比偏移定义。 |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | 返回或设置填充矩形底边缘，该边缘由相对于形状边界框底边缘的百分比偏移定义。 |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | 返回或设置填充矩形底边缘，该边缘由相对于形状边界框底边缘的百分比偏移定义。 |
| [getTileOffsetX()](#getTileOffsetX--) | 返回或设置纹理相对于形状原点的水平偏移（单位为点）。 |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | 返回或设置纹理相对于形状原点的水平偏移（单位为点）。 |
| [getTileOffsetY()](#getTileOffsetY--) | 返回或设置纹理相对于形状原点的垂直偏移（单位为点）。 |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | 返回或设置纹理相对于形状原点的垂直偏移（单位为点）。 |
| [getTileScaleX()](#getTileScaleX--) | 返回或设置纹理填充的水平比例，以百分比表示。 |
| [setTileScaleX(float value)](#setTileScaleX-float-) | 返回或设置纹理填充的水平比例，以百分比表示。 |
| [getTileScaleY()](#getTileScaleY--) | 返回或设置纹理填充的垂直比例，以百分比表示。 |
| [setTileScaleY(float value)](#setTileScaleY-float-) | 返回或设置纹理填充的垂直比例，以百分比表示。 |
| [getTileAlignment()](#getTileAlignment--) | 返回或设置纹理在形状内的对齐方式。 |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | 返回或设置纹理在形状内的对齐方式。 |
| [getTileFlip()](#getTileFlip--) | 在水平、垂直或两个轴上翻转纹理平铺。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 在水平、垂直或两个轴上翻转纹理平铺。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long.

**返回：**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

返回或设置用于填充图片的 dpi。可读写 int .

**返回：**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

返回或设置用于填充图片的 dpi。可读写 int .

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

返回或设置图片填充模式。可读写 [PictureFillMode](../../com.aspose.slides/picturefillmode).

**返回：**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

返回或设置图片填充模式。可读写 [PictureFillMode](../../com.aspose.slides/picturefillmode).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

返回图片。只读 [ISlidesPicture](../../com.aspose.slides/islidespicture).

**返回：**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

返回或设置图片左侧裁剪掉的实际图像宽度的百分比。可读写 float .

**返回：**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

返回或设置图片左侧裁剪掉的实际图像宽度的百分比。可读写 float .

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

返回或设置图片顶部裁剪掉的实际图像高度的百分比。可读写 float .

**返回：**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

返回或设置图片顶部裁剪掉的实际图像高度的百分比。可读写 float .

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

返回或设置图片右侧裁剪掉的实际图像宽度的百分比。可读写 float .

**返回：**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

返回或设置图片右侧裁剪掉的实际图像宽度的百分比。可读写 float .

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

返回或设置图片底部裁剪掉的实际图像高度的百分比。可读写 float .

**返回：**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

返回或设置图片底部裁剪掉的实际图像高度的百分比。可读写 float .

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

删除填充图片的裁剪区域。

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
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```
Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // 使用目标分辨率 150 DPI（网页分辨率）压缩图像并删除裁剪区域
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | int | The target resolution for compression, specified as a value of the [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```
Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 获取 PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // 使用目标分辨率 150 DPI（网页分辨率）压缩图像并删除裁剪区域
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // 网页分辨率
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A  boolean  indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
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

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理的水平偏移设置为 20 点
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理的水平偏移设置为 20 点
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理的垂直偏移设置为 -50 点
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理的垂直偏移设置为 -50 点
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理的水平比例设置为 120 百分比
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理的水平比例设置为 120 百分比
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理的垂直比例设置为 120 百分比
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理的垂直比例设置为 120 百分比
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
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将平铺对齐设置为右下
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

返回或设置纹理在形状内的对齐方式。此设置控制纹理图案的起始点以及它在形状中的重复方式。可读写 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将平铺对齐设置为右下
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
Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 获取形状的图片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 将图片填充模式设置为 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 将纹理平铺围绕垂直轴翻转
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
在水平、垂直或两个轴上翻转纹理平铺。可读写 [TileFlip](../../com.aspose.slides/tileflip).

--------------------

Presentation presentation = new Presentation("demo.pptx");
 try {
     ISlide slide = presentation.getSlides().get_Item(0);
     // 获取形状的图片填充格式
     IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
     // 将图片填充模式设置为 Tile
     pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
     // 在垂直轴上翻转纹理平铺。
     pictureFillFormat.setTileFlip(TileFlip.FlipY);
 } finally {
     if (presentation != null) presentation.dispose();
 }

--------------------

默认是 [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |