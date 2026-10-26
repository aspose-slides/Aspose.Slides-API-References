---
title: IPictureFillFormat
second_title: Aspose.Slides for Java API 參考
description: 表示一種圖片填充樣式。
type: docs
url: /zh-hant/com.aspose.slides/ipicturefillformat/
---
**已實作的所有介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

表示一種圖片填充樣式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDpi()](#getDpi--) | 返回或設定用於填充圖片的 DPI。 |
| [setDpi(int value)](#setDpi-int-) | 返回或設定用於填充圖片的 DPI。 |
| [getPictureFillMode()](#getPictureFillMode--) | 返回或設定圖片填充模式。 |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 返回或設定圖片填充模式。 |
| [getPicture()](#getPicture--) | 返回圖片。 |
| [getCropLeft()](#getCropLeft--) | 返回或設定圖片左側裁剪的實際圖像寬度百分比。 |
| [setCropLeft(float value)](#setCropLeft-float-) | 返回或設定圖片左側裁剪的實際圖像寬度百分比。 |
| [getCropTop()](#getCropTop--) | 返回或設定圖片頂部裁剪的實際圖像高度百分比。 |
| [setCropTop(float value)](#setCropTop-float-) | 返回或設定圖片頂部裁剪的實際圖像高度百分比。 |
| [getCropRight()](#getCropRight--) | 返回或設定圖片右側裁剪的實際圖像寬度百分比。 |
| [setCropRight(float value)](#setCropRight-float-) | 返回或設定圖片右側裁剪的實際圖像寬度百分比。 |
| [getCropBottom()](#getCropBottom--) | 返回或設定圖片底部裁剪的實際圖像高度百分比。 |
| [setCropBottom(float value)](#setCropBottom-float-) | 返回或設定圖片底部裁剪的實際圖像高度百分比。 |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | 返回或設定填充矩形的左邊緣，其以形狀邊界框左邊緣的百分比偏移定義。 |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | 返回或設定填充矩形的左邊緣，其以形狀邊界框左邊緣的百分比偏移定義。 |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | 返回或設定填充矩形的上邊緣，其以形狀邊界框上邊緣的百分比偏移定義。 |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | 返回或設定填充矩形的上邊緣，其以形狀邊界框上邊緣的百分比偏移定義。 |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | 返回或設定填充矩形的右邊緣，其以形狀邊界框右邊緣的百分比偏移定義。 |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | 返回或設定填充矩形的右邊緣，其以形狀邊界框右邊緣的百分比偏移定義。 |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | 返回或設定填充矩形的下邊緣，其以形狀邊界框下邊緣的百分比偏移定義。 |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | 返回或設定填充矩形的下邊緣，其以形狀邊界框下邊緣的百分比偏移定義。 |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 刪除填充圖片的裁剪區域。 |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | 根據形狀大小和指定的解析度壓縮圖像以減少其尺寸。 |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | 根據形狀大小和指定的解析度壓縮圖像以減少其尺寸。 |
| [getTileOffsetX()](#getTileOffsetX--) | 返回或設定紋理相對於形狀原點的水平偏移（單位：點）。 |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | 返回或設定紋理相對於形狀原點的水平偏移（單位：點）。 |
| [getTileOffsetY()](#getTileOffsetY--) | 返回或設定紋理相對於形狀原點的垂直偏移（單位：點）。 |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | 返回或設定紋理相對於形狀原點的垂直偏移（單位：點）。 |
| [getTileScaleX()](#getTileScaleX--) | 返回或設定紋理填充的水平比例（百分比）。 |
| [setTileScaleX(float value)](#setTileScaleX-float-) | 返回或設定紋理填充的水平比例（百分比）。 |
| [getTileScaleY()](#getTileScaleY--) | 返回或設定紋理填充的垂直比例（百分比）。 |
| [setTileScaleY(float value)](#setTileScaleY-float-) | 返回或設定紋理填充的垂直比例（百分比）。 |
| [getTileAlignment()](#getTileAlignment--) | 返回或設定紋理在形狀內的對齊方式。 |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | 返回或設定紋理在形狀內的對齊方式。 |
| [getTileFlip()](#getTileFlip--) | 在水平、垂直或兩個軸上翻轉紋理圖塊。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 在水平、垂直或兩個軸上翻轉紋理圖塊。 |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

返回或設定用於填充圖片的 DPI。讀/寫 int。

**返回：**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

返回或設定用於填充圖片的 DPI。讀/寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

返回或設定圖片填充模式。讀/寫 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**返回：**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

返回或設定圖片填充模式。讀/寫 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

返回圖片。唯讀 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**返回：**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

返回或設定圖片左側裁剪的實際圖像寬度百分比。讀/寫 float。

**返回：**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

返回或設定圖片左側裁剪的實際圖像寬度百分比。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

返回或設定圖片頂部裁剪的實際圖像高度百分比。讀/寫 float。

**返回：**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

返回或設定圖片頂部裁剪的實際圖像高度百分比。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

返回或設定圖片右側裁剪的實際圖像寬度百分比。讀/寫 float。

**返回：**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

返回或設定圖片右側裁剪的實際圖像寬度百分比。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

返回或設定圖片底部裁剪的實際圖像高度百分比。讀/寫 float。

**返回：**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

返回或設定圖片底部裁剪的實際圖像高度百分比。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

返回或設定填充矩形的左邊緣，其以形狀邊界框左邊緣的百分比偏移定義。正數表示內縮，負數表示外伸。讀/寫 float。

**返回：**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

返回或設定填充矩形的左邊緣，其以形狀邊界框左邊緣的百分比偏移定義。正數表示內縮，負數表示外伸。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

返回或設定填充矩形的上邊緣，其以形狀邊界框上邊緣的百分比偏移定義。正數表示內縮，負數表示外伸。讀/寫 float。

**返回：**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

返回或設定填充矩形的上邊緣，其以形狀邊界框上邊緣的百分比偏移定義。正數表示內縮，負數表示外伸。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

返回或設定填充矩形的右邊緣，其以形狀邊界框右邊緣的百分比偏移定義。正數表示內縮，負數表示外伸。讀/寫 float。

**返回：**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

返回或設定填充矩形的右邊緣，其以形狀邊界框右邊緣的百分比偏移定義。正數表示內縮，負數表示外伸。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

返回或設定填充矩形的下邊緣，其以形狀邊界框下邊緣的百分比偏移定義。正數表示內縮，負數表示外伸。讀/寫 float。

**返回：**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

返回或設定填充矩形的下邊緣，其以形狀邊界框下邊緣的百分比偏移定義。正數表示內縮，負數表示外伸。讀/寫 float。

**參數：**
| 參數 | 類型 | 說明 |
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
>      // 取得 PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // 刪除 PictureFrame 圖像的裁剪區域
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
[IPPImage](../../com.aspose.slides/ippimage) - 裁剪後的圖像或如果不需要裁剪則返回原始圖像。

--------------------

此方法將 WMF/EMF 中繼檔轉換為光柵 PNG 圖像，同時進行裁剪。
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

根據形狀大小和指定的解析度壓縮圖像以減少其尺寸。可選地，同時刪除裁剪區域。

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` 方法可通過設定目標解析度並移除裁剪區域來減少演示文稿中圖像的大小：
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
| deleteCroppedAreasOfImage | boolean | 如果為 true，方法將移除圖像的裁剪區域，可能進一步減少其大小。 |
| resolution | int | 壓縮的目標解析度，以 [PicturesCompression](../../com.aspose.slides/picturescompression) 列舉的值指定。

--------------------

此方法會變更圖像的大小與解析度，類似 PowerPoint 的「Picture Format -> Compress Pictures」功能。 |

**Returns:**
boolean - 表示圖像是否成功壓縮的布林值。如果圖像已重新調整大小或裁剪則回傳 true，否則回傳 false。
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> 以下範例說明如何使用 ```
> CompressImage
> ```
 方法透過設定目標解析度並移除裁剪區域來減少演示文稿中圖像的大小：
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) ...
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
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
**參數：**
| 參數 | 類型 | 說明 |
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

預設為 [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**返回:**
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

預設為 [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**參數：**
| 參數 | 類型 | 說明 |
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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |