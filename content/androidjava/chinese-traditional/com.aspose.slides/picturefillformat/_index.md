---
title: PictureFillFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示圖片填充樣式。
type: docs
url: /zh-hant/com.aspose.slides/picturefillformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

表示圖片填充樣式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | 傳回或設定用於填充圖片的 dpi。 |
| [setDpi(int value)](#setDpi-int-) | 傳回或設定用於填充圖片的 dpi。 |
| [getPictureFillMode()](#getPictureFillMode--) | 傳回或設定圖片填充模式。 |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 傳回或設定圖片填充模式。 |
| [getPicture()](#getPicture--) | 傳回圖片。 |
| [getCropLeft()](#getCropLeft--) | 傳回或設定實際圖像寬度的百分比，表示從圖片左側裁切的比例。 |
| [setCropLeft(float value)](#setCropLeft-float-) | 傳回或設定實際圖像寬度的百分比，表示從圖片左側裁切的比例。 |
| [getCropTop()](#getCropTop--) | 傳回或設定實際圖像高度的百分比，表示從圖片頂部裁切的比例。 |
| [setCropTop(float value)](#setCropTop-float-) | 傳回或設定實際圖像高度的百分比，表示從圖片頂部裁切的比例。 |
| [getCropRight()](#getCropRight--) | 傳回或設定實際圖像寬度的百分比，表示從圖片右側裁切的比例。 |
| [setCropRight(float value)](#setCropRight-float-) | 傳回或設定實際圖像寬度的百分比，表示從圖片右側裁切的比例。 |
| [getCropBottom()](#getCropBottom--) | 傳回或設定實際圖像高度的百分比，表示從圖片底部裁切的比例。 |
| [setCropBottom(float value)](#setCropBottom-float-) | 傳回或設定實際圖像高度的百分比，表示從圖片底部裁切的比例。 |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 刪除填充圖片的裁剪區域。 |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | 根據形狀大小和指定的解析度壓縮圖像以減小其尺寸。 |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | 根據形狀大小和指定的解析度壓縮圖像以減小其尺寸。 |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | 傳回或設定填充矩形的左邊緣，該邊緣以相對於形狀邊界框左邊緣的百分比偏移定義。 |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | 傳回或設定填充矩形的左邊緣，該邊緣以相對於形狀邊界框左邊緣的百分比偏移定義。 |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | 傳回或設定填充矩形的頂邊緣，該邊緣以相對於形狀邊界框頂邊緣的百分比偏移定義。 |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | 傳回或設定填充矩形的頂邊緣，該邊緣以相對於形狀邊界框頂邊緣的百分比偏移定義。 |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | 傳回或設定填充矩形的右邊緣，該邊緣以相對於形狀邊界框右邊緣的百分比偏移定義。 |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | 傳回或設定填充矩形的右邊緣，該邊緣以相對於形狀邊界框右邊緣的百分比偏移定義。 |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | 傳回或設定填充矩形的底邊緣，該邊緣以相對於形狀邊界框底邊緣的百分比偏移定義。 |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | 傳回或設定填充矩形的底邊緣，該邊緣以相對於形狀邊界框底邊緣的百分比偏移定義。 |
| [getTileOffsetX()](#getTileOffsetX--) | 傳回或設定紋理相對於形狀原點的水平偏移（以點為單位）。 |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | 傳回或設定紋理相對於形狀原點的水平偏移（以點為單位）。 |
| [getTileOffsetY()](#getTileOffsetY--) | 傳回或設定紋理相對於形狀原點的垂直偏移（以點為單位）。 |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | 傳回或設定紋理相對於形狀原點的垂直偏移（以點為單位）。 |
| [getTileScaleX()](#getTileScaleX--) | 傳回或設定紋理填充的水平比例（以百分比表示）。 |
| [setTileScaleX(float value)](#setTileScaleX-float-) | 傳回或設定紋理填充的水平比例（以百分比表示）。 |
| [getTileScaleY()](#getTileScaleY--) | 傳回或設定紋理填充的垂直比例（以百分比表示）。 |
| [setTileScaleY(float value)](#setTileScaleY-float-) | 傳回或設定紋理填充的垂直比例（以百分比表示）。 |
| [getTileAlignment()](#getTileAlignment--) | 傳回或設定紋理在形狀內的對齊方式。 |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | 傳回或設定紋理在形狀內的對齊方式。 |
| [getTileFlip()](#getTileFlip--) | 沿水平、垂直或兩個軸翻轉紋理平鋪。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 沿水平、垂直或兩個軸翻轉紋理平鋪。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回：**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

傳回或設定用於填充圖片的 dpi。可讀寫 int 。

**傳回：**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

傳回或設定用於填充圖片的 dpi。可讀寫 int 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

傳回或設定圖片填充模式。可讀寫 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**傳回：**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

傳回或設定圖片填充模式。可讀寫 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

傳回圖片。唯讀 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**傳回：**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

傳回或設定實際圖像寬度的百分比，表示從圖片左側裁切的比例。可讀寫 float 。

**傳回：**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

傳回或設定實際圖像寬度的百分比，表示從圖片左側裁切的比例。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

傳回或設定實際圖像高度的百分比，表示從圖片頂部裁切的比例。可讀寫 float 。

**傳回：**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

傳回或設定實際圖像高度的百分比，表示從圖片頂部裁切的比例。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

傳回或設定實際圖像寬度的百分比，表示從圖片右側裁切的比例。可讀寫 float 。

**傳回：**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

傳回或設定實際圖像寬度的百分比，表示從圖片右側裁切的比例。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

傳回或設定實際圖像高度的百分比，表示從圖片底部裁切的比例。可讀寫 float 。

**傳回：**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

傳回或設定實際圖像高度的百分比，表示從圖片底部裁切的比例。可讀寫 float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

刪除填充圖片的裁剪區域。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 取得 PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // 刪除 PictureFrame 影像的裁剪區域
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**傳回：**
[IPPImage](../../com.aspose.slides/ippimage) - 裁剪後的圖像，若不需裁剪則返回原始圖像。

--------------------

此方法在裁剪的同時，將 WMF/EMF 中繪圖檔轉換為光柵 PNG 圖像。

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

根據形狀大小和指定的解析度壓縮圖像以減小其尺寸。必要時也會刪除裁剪區域。

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` 方法，用於透過設定目標解析度並移除裁剪區域來減少簡報中圖像的大小：
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // 壓縮圖像，目標解析度為 150 DPI（網頁解析度），同時移除裁剪區域
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | 如果為 true，方法將移除影像的裁剪區域，可能進一步減小其大小。 |
| resolution | int | 壓縮的目標解析度，以 [PicturesCompression](../../com.aspose.slides/picturescompression) 列舉的值指定。 |

--------------------

此方法會變更影像的大小與解析度，類似 PowerPoint 的「圖片格式 -> 壓縮圖片」功能。 |

**傳回值：**
boolean - 表示是否成功壓縮影像的布林值。若影像已被重新調整大小或裁剪則傳回   ，否則傳回  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> 以下範例示範如何使用 ```
> CompressImage
> ```
 方法透過設定目標解析度並移除裁剪區域來減少簡報中圖像的大小：
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 取得 PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // 壓縮圖像，目標解析度為 150 DPI（網頁解析度），同時移除裁剪區域
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // 網頁解析度
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

傳回或設定填充矩形的底邊緣，該邊緣以相對於形狀邊界框底邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外延。可讀寫  float .

**傳回：**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定紋理的水平偏移為 20 點
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定紋理的水平偏移為 20 點
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定紋理的垂直偏移為 -50 點
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定紋理的垂直偏移為 -50 點
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定紋理的水平比例為 120%
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定紋理的水平比例為 120%
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定紋理的垂直比例為 120%
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**傳回：**
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定紋理的垂直比例為 120%
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**參數:**
| 參數 | 類型 | 說明 |
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定平鋪的對齊方式為右下角
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 設定平鋪的對齊方式為右下角
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
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 沿垂直軸翻轉紋理平鋪
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


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // 取得形狀的圖片填充格式
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // 設定圖片填充模式為 Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // 沿垂直軸翻轉紋理平鋪
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

預設為 [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |