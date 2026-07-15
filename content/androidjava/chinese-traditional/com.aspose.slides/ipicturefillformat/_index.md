---
title: IPictureFillFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示圖片填充樣式。
type: docs
url: /zh-hant/com.aspose.slides/ipicturefillformat/
---
**所有已實作的介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

表示圖片填充樣式。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getDpi()](#getDpi--) | 傳回或設定用於填充圖片的 dpi。 |
| [setDpi(int value)](#setDpi-int-) | 傳回或設定用於填充圖片的 dpi。 |
| [getPictureFillMode()](#getPictureFillMode--) | 傳回或設定圖片填充模式。 |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 傳回或設定圖片填充模式。 |
| [getPicture()](#getPicture--) | 傳回圖片。 |
| [getCropLeft()](#getCropLeft--) | 傳回或設定圖片左側裁剪的實際圖像寬度百分比。 |
| [setCropLeft(float value)](#setCropLeft-float-) | 傳回或設定圖片左側裁剪的實際圖像寬度百分比。 |
| [getCropTop()](#getCropTop--) | 傳回或設定圖片上方裁剪的實際圖像高度百分比。 |
| [setCropTop(float value)](#setCropTop-float-) | 傳回或設定圖片上方裁剪的實際圖像高度百分比。 |
| [getCropRight()](#getCropRight--) | 傳回或設定圖片右側裁剪的實際圖像寬度百分比。 |
| [setCropRight(float value)](#setCropRight-float-) | 傳回或設定圖片右側裁剪的實際圖像寬度百分比。 |
| [getCropBottom()](#getCropBottom--) | 傳回或設定圖片下方裁剪的實際圖像高度百分比。 |
| [setCropBottom(float value)](#setCropBottom-float-) | 傳回或設定圖片下方裁剪的實際圖像高度百分比。 |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | 傳回或設定填充矩形的左邊緣，該邊緣以形狀邊界框左邊緣的百分比偏移定義。 |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | 傳回或設定填充矩形的左邊緣，該邊緣以形狀邊界框左邊緣的百分比偏移定義。 |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | 傳回或設定填充矩形的上邊緣，該邊緣以形狀邊界框上邊緣的百分比偏移定義。 |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | 傳回或設定填充矩形的上邊緣，該邊緣以形狀邊界框上邊緣的百分比偏移定義。 |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | 傳回或設定填充矩形的右邊緣，該邊緣以形狀邊界框右邊緣的百分比偏移定義。 |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | 傳回或設定填充矩形的右邊緣，該邊緣以形狀邊界框右邊緣的百分比偏移定義。 |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | 傳回或設定填充矩形的下邊緣，該邊緣以形狀邊界框下邊緣的百分比偏移定義。 |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | 傳回或設定填充矩形的下邊緣，該邊緣以形狀邊界框下邊緣的百分比偏移定義。 |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 刪除填充圖片的裁剪區域。 |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | 根據形狀大小和指定的解析度壓縮圖像。 |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | 根據形狀大小和指定的解析度壓縮圖像。 |
| [getTileOffsetX()](#getTileOffsetX--) | 傳回或設定紋理相對於形狀原點的水平偏移（點）。 |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | 傳回或設定紋理相對於形狀原點的水平偏移（點）。 |
| [getTileOffsetY()](#getTileOffsetY--) | 傳回或設定紋理相對於形狀原點的垂直偏移（點）。 |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | 傳回或設定紋理相對於形狀原點的垂直偏移（點）。 |
| [getTileScaleX()](#getTileScaleX--) | 傳回或設定紋理填充的水平比例（百分比）。 |
| [setTileScaleX(float value)](#setTileScaleX-float-) | 傳回或設定紋理填充的水平比例（百分比）。 |
| [getTileScaleY()](#getTileScaleY--) | 傳回或設定紋理填充的垂直比例（百分比）。 |
| [setTileScaleY(float value)](#setTileScaleY-float-) | 傳回或設定紋理填充的垂直比例（百分比）。 |
| [getTileAlignment()](#getTileAlignment--) | 傳回或設定紋理在形狀內的對齊方式。 |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | 傳回或設定紋理在形狀內的對齊方式。 |
| [getTileFlip()](#getTileFlip--) | 圍繞水平、垂直或兩個軸翻轉紋理瓦片。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 圍繞水平、垂直或兩個軸翻轉紋理瓦片。 |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

傳回或設定用於填充圖片的 dpi。讀寫 int。

**傳回：**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

傳回或設定用於填充圖片的 dpi。讀寫 int。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

傳回或設定圖片填充模式。讀寫 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**傳回：**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

傳回或設定圖片填充模式。讀寫 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

傳回圖片。唯讀 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**傳回：**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

傳回或設定圖片左側裁剪的實際圖像寬度百分比。讀寫 float。

**傳回：**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

傳回或設定圖片左側裁剪的實際圖像寬度百分比。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

傳回或設定圖片上方裁剪的實際圖像高度百分比。讀寫 float。

**傳回：**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

傳回或設定圖片上方裁剪的實際圖像高度百分比。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

傳回或設定圖片右側裁剪的實際圖像寬度百分比。讀寫 float。

**傳回：**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

傳回或設定圖片右側裁剪的實際圖像寬度百分比。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

傳回或設定圖片下方裁剪的實際圖像高度百分比。讀寫 float。

**傳回：**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

傳回或設定圖片下方裁剪的實際圖像高度百分比。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

傳回或設定填充矩形的左邊緣，該邊緣以形狀邊界框左邊緣的百分比偏移定義。正值表示內縮，負值表示外擴。讀寫 float。

**傳回：**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

傳回或設定填充矩形的左邊緣，該邊緣以形狀邊界框左邊緣的百分比偏移定義。正值表示內縮，負值表示外擴。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

傳回或設定填充矩形的上邊緣，該邊緣以形狀邊界框上邊緣的百分比偏移定義。正值表示內縮，負值表示外擴。讀寫 float。

**傳回：**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

傳回或設定填充矩形的上邊緣，該邊緣以形狀邊界框上邊緣的百分比偏移定義。正值表示內縮，負值表示外擴。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

傳回或設定填充矩形的右邊緣，該邊緣以形狀邊界框右邊緣的百分比偏移定義。正值表示內縮，負值表示外擴。讀寫 float。

**傳回：**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

傳回或設定填充矩形的右邊緣，該邊緣以形狀邊界框右邊緣的百分比偏移定義。正值表示內縮，負值表示外擴。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

傳回或設定填充矩形的下邊緣，該邊緣以形狀邊界框下邊緣的百分比偏移定義。正值表示內縮，負值表示外擴。讀寫 float。

**傳回：**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

傳回或設定填充矩形的下邊緣，該邊緣以形狀邊界框下邊緣的百分比偏移定義。正值表示內縮，負值表示外擴。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

刪除填充圖片的裁剪區域。

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

**傳回：**
[IPPImage](../../com.aspose.slides/ippimage) - 裁剪圖像或若不需裁剪則返回原始圖像。

--------------------

此方法在裁剪的同時，將 WMF/EMF 元檔轉換為光柵 PNG 圖像。

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

根據形狀大小和指定的解析度壓縮圖像。必要時亦會刪除裁剪區域。

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` 方法用於透過設定目標解析度並移除裁剪區域以減少簡報中圖像的大小：
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
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
> 以下範例示範如何使用 ```
> CompressImage
> ``` 方法透過設定目標解析度並移除裁剪區域來減少簡報中圖像的大小：
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | 如果為 true，方法將移除圖像的裁剪區域，可能會進一步減少其大小。 |
| resolution | float | 目標解析度（DPI）。此值必須為正數，並定義圖像將如何被重新調整大小。 |
--------------------

此方法會改變圖像的大小和解析度，類似於 PowerPoint 的「Picture Format -> Compress Pictures」功能。 |

**傳回值：**
boolean - 布林值，表示圖像是否成功壓縮。若圖像已被重新調整大小或裁剪則回傳 true，否則回傳 false。
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
public abstract void setTileOffsetX(float value)
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
public abstract float getTileOffsetY()
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
public abstract void setTileOffsetY(float value)
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

**參數：**
| 參數 | 類型 | 說明 |
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
public abstract void setTileScaleX(float value)
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
public abstract float getTileScaleY()
```
傳回或設定紋理填充的垂直比例（百分比）。讀寫  float .
```
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
public abstract void setTileScaleY(float value)
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
public abstract int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

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
public abstract void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

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

預設為 [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |