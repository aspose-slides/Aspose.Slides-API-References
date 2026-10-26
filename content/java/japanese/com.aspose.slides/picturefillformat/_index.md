---
title: PictureFillFormat
second_title: Aspose.Slides for Java APIリファレンス
description: 画像の塗りつぶしスタイルを表します。
type: docs
url: /ja/com.aspose.slides/picturefillformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)  
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

画像塗りつぶしスタイルを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | 画像の塗りつぶしに使用される dpi を取得または設定します。 |
| [setDpi(int value)](#setDpi-int-) | 画像の塗りつぶしに使用される dpi を取得または設定します。 |
| [getPictureFillMode()](#getPictureFillMode--) | 画像の塗りつぶしモードを取得または設定します。 |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 画像の塗りつぶしモードを取得または設定します。 |
| [getPicture()](#getPicture--) | 画像を取得します。 |
| [getCropLeft()](#getCropLeft--) | 画像の左側から切り取られる実際の画像幅のパーセンテージを取得または設定します。 |
| [setCropLeft(float value)](#setCropLeft-float-) | 画像の左側から切り取られる実際の画像幅のパーセンテージを取得または設定します。 |
| [getCropTop()](#getCropTop--) | 画像の上側から切り取られる実際の画像高さのパーセンテージを取得または設定します。 |
| [setCropTop(float value)](#setCropTop-float-) | 画像の上側から切り取られる実際の画像高さのパーセンテージを取得または設定します。 |
| [getCropRight()](#getCropRight--) | 画像の右側から切り取られる実際の画像幅のパーセンテージを取得または設定します。 |
| [setCropRight(float value)](#setCropRight-float-) | 画像の右側から切り取られる実際の画像幅のパーセンテージを取得または設定します。 |
| [getCropBottom()](#getCropBottom--) | 画像の下側から切り取られる実際の画像高さのパーセンテージを取得または設定します。 |
| [setCropBottom(float value)](#setCropBottom-float-) | 画像の下側から切り取られる実際の画像高さのパーセンテージを取得または設定します。 |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 塗りつぶし画像の切り抜かれた領域を削除します。 |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | シェイプのサイズと指定された解像度に基づいて画像サイズを縮小し、画像を圧縮します。 |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | シェイプのサイズと指定された解像度に基づいて画像サイズを縮小し、画像を圧縮します。 |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | シェイプの境界ボックスの左端からのパーセンテージオフセットで定義された塗りつぶし矩形の左端を取得または設定します。 |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | シェイプの境界ボックスの左端からのパーセンテージオフセットで定義された塗りつぶし矩形の左端を取得または設定します。 |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | シェイプの境界ボックスの上端からのパーセンテージオフセットで定義された塗りつぶし矩形の上端を取得または設定します。 |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | シェイプの境界ボックスの上端からのパーセンテージオフセットで定義された塗りつぶし矩形の上端を取得または設定します。 |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | シェイプの境界ボックスの右端からのパーセンテージオフセットで定義された塗りつぶし矩形の右端を取得または設定します。 |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | シェイプの境界ボックスの右端からのパーセンテージオフセットで定義された塗りつぶし矩形の右端を取得または設定します。 |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | シェイプの境界ボックスの下端からのパーセンテージオフセットで定義された塗りつぶし矩形の下端を取得または設定します。 |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | シェイプの境界ボックスの下端からのパーセンテージオフセットで定義された塗りつぶし矩形の下端を取得または設定します。 |
| [getTileOffsetX()](#getTileOffsetX--) | シェイプの原点からテクスチャの水平オフセットをポイント単位で取得または設定します。 |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | シェイプの原点からテクスチャの水平オフセットをポイント単位で取得または設定します。 |
| [getTileOffsetY()](#getTileOffsetY--) | シェイプの原点からテクスチャの垂直オフセットをポイント単位で取得または設定します。 |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | シェイプの原点からテクスチャの垂直オフセットをポイント単位で取得または設定します。 |
| [getTileScaleX()](#getTileScaleX--) | テクスチャ塗りつぶしの水平スケールをパーセンテージで取得または設定します。 |
| [setTileScaleX(float value)](#setTileScaleX-float-) | テクスチャ塗りつぶしの水平スケールをパーセンテージで取得または設定します。 |
| [getTileScaleY()](#getTileScaleY--) | テクスチャ塗りつぶしの垂直スケールをパーセンテージで取得または設定します。 |
| [setTileScaleY(float value)](#setTileScaleY-float-) | テクスチャ塗りつぶしの垂直スケールをパーセンテージで取得または設定します。 |
| [getTileAlignment()](#getTileAlignment--) | テクスチャがシェイプ内でどのように配置されるかを取得または設定します。 |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | テクスチャがシェイプ内でどのように配置されるかを取得または設定します。 |
| [getTileFlip()](#getTileFlip--) | テクスチャタイルを水平、垂直、またはその両方の軸で反転させます。 |
| [setTileFlip(int value)](#setTileFlip-int-) | テクスチャタイルを水平、垂直、またはその両方の軸で反転させます。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. 読み取り専用 long.

**戻り値:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

画像の塗りつぶしに使用される dpi を取得または設定します。読み書き int .

**戻り値:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

画像の塗りつぶしに使用される dpi を取得または設定します。読み書き int .

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

画像の塗りつぶしモードを取得または設定します。読み書き [PictureFillMode](../../com.aspose.slides/picturefillmode).

**戻り値:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

画像の塗りつぶしモードを取得または設定します。読み書き [PictureFillMode](../../com.aspose.slides/picturefillmode).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

画像を取得します。読み取り専用 [ISlidesPicture](../../com.aspose.slides/islidespicture).

**戻り値:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

画像の左側から切り取られる実際の画像幅のパーセンテージを取得または設定します。読み書き float .

**戻り値:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

画像の左側から切り取られる実際の画像幅のパーセンテージを取得または設定します。読み書き float .

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

画像の上側から切り取られる実際の画像高さのパーセンテージを取得または設定します。読み書き float .

**戻り値:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

画像の上側から切り取られる実際の画像高さのパーセンテージを取得または設定します。読み書き float .

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

画像の右側から切り取られる実際の画像幅のパーセンテージを取得または設定します。読み書き float .

**戻り値:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

画像の右側から切り取られる実際の画像幅のパーセンテージを取得または設定します。読み書き float .

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

画像の下側から切り取られる実際の画像高さのパーセンテージを取得または設定します。読み書き float .

**戻り値:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

画像の下側から切り取られる実際の画像高さのパーセンテージを取得または設定します。読み書き float .

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

塗りつぶし画像の切り抜かれた領域を削除します。

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
[IPPImage](../../com.aspose.slides/ippimage) - 切り抜かれた画像、または切り抜きが不要な場合は元画像

--------------------

このメソッドは WMF/EMF メタファイルをラスタ PNG 画像に変換し、切り抜きを行います。

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

シェイプのサイズと指定された解像度に基づいて画像サイズを縮小し、画像を圧縮します。必要に応じて切り抜かれた領域も削除します。

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` プレゼンテーション内の画像のサイズを、目標解像度を設定し、切り抜かれた領域を削除することで縮小するメソッド:
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
 メソッドを使用して、目標解像度を設定し、切り抜き領域を削除することでプレゼンテーション内の画像サイズを縮小する方法を示しています:
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | true の場合、メソッドは画像の切り取られた領域を削除し、サイズをさらに縮小できる可能性があります。 |
| resolution | float | DPI 単位の目標解像度。この値は正の数である必要があり、画像のリサイズ方法を定義します。

--------------------

このメソッドは、PowerPoint の「Picture Format -> Compress Pictures」機能と同様に、画像のサイズと解像度を変更します。 |

**戻り値:**
boolean - 画像が正常に圧縮されたかどうかを示す boolean。画像がリサイズまたは切り取られた場合は   を返し、それ以外の場合は  を返します。
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```

シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義される塗りつぶし矩形の左端を取得または設定します。正のパーセンテージはインセットを、負のパーセンテージはアウトセットを指定します。読み書き可能な float .

**戻り値:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義される塗りつぶし矩形の左端を取得または設定します。正のパーセンテージはインセットを、負のパーセンテージはアウトセットを指定します。読み書き可能な float .

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public final float getStretchOffsetTop()
```

シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義される塗りつぶし矩形の上端を取得または設定します。正のパーセンテージはインセットを、負のパーセンテージはアウトセットを指定します。読み書き可能な float .

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

**パラメーター:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |