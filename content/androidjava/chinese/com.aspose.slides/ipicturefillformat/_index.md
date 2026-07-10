---
title: IPictureFillFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图片填充样式。
type: docs
url: /zh/com.aspose.slides/ipicturefillformat/
---
**已实现的接口：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

表示图片填充样式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDpi()](#getDpi--) | 返回或设置用于填充图片的 dpi。 |
| [setDpi(int value)](#setDpi-int-) | 返回或设置用于填充图片的 dpi。 |
| [getPictureFillMode()](#getPictureFillMode--) | 返回或设置图片填充模式。 |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 返回或设置图片填充模式。 |
| [getPicture()](#getPicture--) | 返回图片。 |
| [getCropLeft()](#getCropLeft--) | 返回或设置从图片左侧裁剪的实际图像宽度的百分比。 |
| [setCropLeft(float value)](#setCropLeft-float-) | 返回或设置从图片左侧裁剪的实际图像宽度的百分比。 |
| [getCropTop()](#getCropTop--) | 返回或设置从图片顶部裁剪的实际图像高度的百分比。 |
| [setCropTop(float value)](#setCropTop-float-) | 返回或设置从图片顶部裁剪的实际图像高度的百分比。 |
| [getCropRight()](#getCropRight--) | 返回或设置从图片右侧裁剪的实际图像宽度的百分比。 |
| [setCropRight(float value)](#setCropRight-float-) | 返回或设置从图片右侧裁剪的实际图像宽度的百分比。 |
| [getCropBottom()](#getCropBottom--) | 返回或设置从图片底部裁剪的实际图像高度的百分比。 |
| [setCropBottom(float value)](#setCropBottom-float-) | 返回或设置从图片底部裁剪的实际图像高度的百分比。 |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | 返回或设置填充矩形的左边缘，该边缘由相对于形状边界框左边缘的百分比偏移定义。 |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | 返回或设置填充矩形的左边缘，该边缘由相对于形状边界框左边缘的百分比偏移定义。 |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | 返回或设置填充矩形的上边缘，该边缘由相对于形状边界框顶部的百分比偏移定义。 |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | 返回或设置填充矩形的上边缘，该边缘由相对于形状边界框顶部的百分比偏移定义。 |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | 返回或设置填充矩形的右边缘，该边缘由相对于形状边界框右边缘的百分比偏移定义。 |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | 返回或设置填充矩形的右边缘，该边缘由相对于形状边界框右边缘的百分比偏移定义。 |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | 返回或设置填充矩形的下边缘，该边缘由相对于形状边界框底部的百分比偏移定义。 |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | 返回或设置填充矩形的下边缘，该边缘由相对于形状边界框底部的百分比偏移定义。 |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 删除填充图片的裁剪区域。 |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | 通过根据形状大小和指定分辨率缩小图像来压缩图像。 |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | 通过根据形状大小和指定分辨率缩小图像来压缩图像。 |
| [getTileOffsetX()](#getTileOffsetX--) | 返回或设置纹理相对于形状原点的水平偏移（点）。 |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | 返回或设置纹理相对于形状原点的水平偏移（点）。 |
| [getTileOffsetY()](#getTileOffsetY--) | 返回或设置纹理相对于形状原点的垂直偏移（点）。 |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | 返回或设置纹理相对于形状原点的垂直偏移（点）。 |
| [getTileScaleX()](#getTileScaleX--) | 返回或设置纹理填充的水平比例（百分比）。 |
| [setTileScaleX(float value)](#setTileScaleX-float-) | 返回或设置纹理填充的水平比例（百分比）。 |
| [getTileScaleY()](#getTileScaleY--) | 返回或设置纹理填充的垂直比例（百分比）。 |
| [setTileScaleY(float value)](#setTileScaleY-float-) | 返回或设置纹理填充的垂直比例（百分比）。 |
| [getTileAlignment()](#getTileAlignment--) | 返回或设置纹理在形状内的对齐方式。 |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | 返回或设置纹理在形状内的对齐方式。 |
| [getTileFlip()](#getTileFlip--) | 在水平、垂直或两个轴上翻转纹理平铺。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 在水平、垂直或两个轴上翻转纹理平铺。 |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

返回或设置用于填充图片的 dpi。读/写 int。

**返回：**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

返回或设置用于填充图片的 dpi。读/写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

返回或设置图片填充模式。读/写 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**返回：**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

返回或设置图片填充模式。读/写 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

返回图片。只读 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**返回：**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

返回或设置从图片左侧裁剪的实际图像宽度的百分比。读/写 float。

**返回：**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

返回或设置从图片左侧裁剪的实际图像宽度的百分比。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

返回或设置从图片顶部裁剪的实际图像高度的百分比。读/写 float。

**返回：**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

返回或设置从图片顶部裁剪的实际图像高度的百分比。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

返回或设置从图片右侧裁剪的实际图像宽度的百分比。读/写 float。

**返回：**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

返回或设置从图片右侧裁剪的实际图像宽度的百分比。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

返回或设置从图片底部裁剪的实际图像高度的百分比。读/写 float。

**返回：**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

返回或设置从图片底部裁剪的实际图像高度的百分比。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

返回或设置填充矩形的左边缘，该边缘由相对于形状边界框左边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。读/写 float。

**返回：**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

返回或设置填充矩形的左边缘，该边缘由相对于形状边界框左边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

返回或设置填充矩形的上边缘，该边缘由相对于形状边界框顶部的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。读/写 float。

**返回：**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

返回或设置填充矩形的上边缘，该边缘由相对于形状边界框顶部的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

返回或设置填充矩形的右边缘，该边缘由相对于形状边界框右边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。读/写 float。

**返回：**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

返回或设置填充矩形的右边缘，该边缘由相对于形状边界框右边缘的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

返回或设置填充矩形的下边缘，该边缘由相对于形状边界框底部的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。读/写 float。

**返回：**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

返回或设置填充矩形的下边缘，该边缘由相对于形状边界框底部的百分比偏移定义。正百分比表示内缩，负百分比表示外伸。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
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
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
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
>      // 压缩图像，目标分辨率为 150 DPI（网页分辨率），并删除裁剪区域
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
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
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
>      // 压缩图像，目标分辨率为 150 DPI（网页分辨率），并删除裁剪区域
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
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### getTileOffsetX() {#getTileOffsetX--}
```
public abstract float getTileOffsetX()
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
public abstract void setTileOffsetX(float value)
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
public abstract float getTileOffsetY()
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
public abstract void setTileOffsetY(float value)
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
public abstract float getTileScaleX()
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
>      // 将纹理的水平比例设置为 120%
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public abstract void setTileScaleX(float value)
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
>      // 将纹理的水平比例设置为 120%
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
```
public abstract float getTileScaleY()
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
>      // 将纹理的垂直比例设置为 120%
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public abstract void setTileScaleY(float value)
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
>      // 将纹理的垂直比例设置为 120%
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
public abstract byte getTileAlignment()
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
public abstract void setTileAlignment(byte value)
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
>      // 将平铺的对齐方式设置为右下角
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
public abstract int getTileFlip()
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
>      // 将纹理平铺在垂直轴上翻转
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
public abstract void setTileFlip(int value)

在水平、垂直或两个轴上翻转纹理平铺。读/写 [TileFlip](../../com.aspose.slides/tileflip)。

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

默认是 [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |