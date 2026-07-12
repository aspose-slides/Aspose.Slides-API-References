---
title: PictureFillFormat
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: 画像の塗りつぶしスタイルを表します。
type: docs
url: /ja/com.aspose.slides/picturefillformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)  
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

画像塗りつぶしスタイルを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | 画像を塗りつぶす際に使用される dpi を取得または設定します。 |
| [setDpi(int value)](#setDpi-int-) | 画像を塗りつぶす際に使用される dpi を取得または設定します。 |
| [getPictureFillMode()](#getPictureFillMode--) | 画像塗りつぶしモードを取得または設定します。 |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 画像塗りつぶしモードを取得または設定します。 |
| [getPicture()](#getPicture--) | 画像を取得します。 |
| [getCropLeft()](#getCropLeft--) | 画像の左側から切り取られる実際の画像幅のパーセンテージを取得または設定します。 |
| [setCropLeft(float value)](#setCropLeft-float-) | 画像の左側から切り取られる実際の画像幅のパーセンテージを取得または設定します。 |
| [getCropTop()](#getCropTop--) | 画像の上部から切り取られる実際の画像高さのパーセンテージを取得または設定します。 |
| [setCropTop(float value)](#setCropTop-float-) | 画像の上部から切り取られる実際の画像高さのパーセンテージを取得または設定します。 |
| [getCropRight()](#getCropRight--) | 画像の右側から切り取られる実際の画像幅のパーセンテージを取得または設定します。 |
| [setCropRight(float value)](#setCropRight-float-) | 画像の右側から切り取られる実際の画像幅のパーセンテージを取得または設定します。 |
| [getCropBottom()](#getCropBottom--) | 画像の下部から切り取られる実際の画像高さのパーセンテージを取得または設定します。 |
| [setCropBottom(float value)](#setCropBottom-float-) | 画像の下部から切り取られる実際の画像高さのパーセンテージを取得または設定します。 |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 塗りつぶし画像の切り取られた領域を削除します。 |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | シェイプのサイズと指定された解像度に基づいて画像のサイズを縮小し、圧縮します。 |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | シェイプのサイズと指定された解像度に基づいて画像のサイズを縮小し、圧縮します。 |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義される塗りつぶし矩形の左端を取得または設定します。 |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義される塗りつぶし矩形の左端を取得または設定します。 |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義される塗りつぶし矩形の上端を取得または設定します。 |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義される塗りつぶし矩形の上端を取得または設定します。 |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義される塗りつぶし矩形の右端を取得または設定します。 |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義される塗りつぶし矩形の右端を取得または設定します。 |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義される塗りつぶし矩形の下端を取得または設定します。 |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義される塗りつぶし矩形の下端を取得または設定します。 |
| [getTileOffsetX()](#getTileOffsetX--) | シェイプの原点からテクスチャの水平方向オフセット（ポイント単位）を取得または設定します。 |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | シェイプの原点からテクスチャの水平方向オフセット（ポイント単位）を取得または設定します。 |
| [getTileOffsetY()](#getTileOffsetY--) | シェイプの原点からテクスチャの垂直方向オフセット（ポイント単位）を取得または設定します。 |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | シェイプの原点からテクスチャの垂直方向オフセット（ポイント単位）を取得または設定します。 |
| [getTileScaleX()](#getTileScaleX--) | テクスチャ塗りつぶしの水平方向スケールをパーセンテージで取得または設定します。 |
| [setTileScaleX(float value)](#setTileScaleX-float-) | テクスチャ塗りつぶしの水平方向スケールをパーセンテージで取得または設定します。 |
| [getTileScaleY()](#getTileScaleY--) | テクスチャ塗りつぶしの垂直方向スケールをパーセンテージで取得または設定します。 |
| [setTileScaleY(float value)](#setTileScaleY-float-) | テクスチャ塗りつぶしの垂直方向スケールをパーセンテージで取得または設定します。 |
| [getTileAlignment()](#getTileAlignment--) | テクスチャがシェイプ内でどのように配置されるかを取得または設定します。 |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | テクスチャがシェイプ内でどのように配置されるかを取得または設定します。 |
| [getTileFlip()](#getTileFlip--) | テクスチャタイルを水平方向、垂直方向、または両方の軸で反転させます。 |
| [setTileFlip(int value)](#setTileFlip-int-) | テクスチャタイルを水平方向、垂直方向、または両方の軸で反転させます。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

画像を塗りつぶす際に使用される dpi を取得または設定します。読み書き可能 int 。

**戻り値:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

画像を塗りつぶす際に使用される dpi を取得または設定します。読み書き可能 int 。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

画像塗りつぶしモードを取得または設定します。読み書き可能 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**戻り値:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

画像塗りつぶしモードを取得または設定します。読み書き可能 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

画像を取得します。読み取り専用 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**戻り値:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

画像の左側から切り取られる実際の画像幅のパーセンテージを取得または設定します。読み書き可能 float 。

**戻り値:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

画像の左側から切り取られる実際の画像幅のパーセンテージを取得または設定します。読み書き可能 float 。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

画像の上部から切り取られる実際の画像高さのパーセンテージを取得または設定します。読み書き可能 float 。

**戻り値:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

画像の上部から切り取られる実際の画像高さのパーセンテージを取得または設定します。読み書き可能 float 。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

画像の右側から切り取られる実際の画像幅のパーセンテージを取得または設定します。読み書き可能 float 。

**戻り値:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

画像の右側から切り取られる実際の画像幅のパーセンテージを取得または設定します。読み書き可能 float 。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

画像の下部から切り取られる実際の画像高さのパーセンテージを取得または設定します。読み書き可能 float 。

**戻り値:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

画像の下部から切り取られる実際の画像高さのパーセンテージを取得または設定します。読み書き可能 float 。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

塗りつぶし画像の切り取られた領域を削除します。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // PictureFrame を取得します
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // PictureFrame 画像の切り取られた領域を削除します
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage) - 切り取られた画像、または切り取りが不要な場合は元画像。

--------------------

このメソッドは WMF/EMF メタファイルをラスタ PNG 画像に変換し、切り取ります。

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

シェイプのサイズと指定された解像度に基づいて画像のサイズを縮小し、圧縮します。オプションで、切り取られた領域も削除します。

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` メソッドは、ターゲット解像度を設定し、切り取られた領域を削除することでプレゼンテーション内の画像サイズを縮小します：
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
boolean - A boolean indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> 以下の例は、```
> CompressImage
> ```
 メソッドを使用して、ターゲット解像度を設定し、切り取られた領域を削除することでプレゼンテーション内の画像サイズを縮小する方法を示しています：
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
public final void setTileFlip(int value)
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

デフォルトは [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip) です。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |