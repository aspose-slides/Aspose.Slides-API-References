---
title: IPictureFillFormat
second_title: Aspose.Slides for Java API リファレンス
description: 画像の塗りつぶしスタイルを表します。
type: docs
url: /ja/com.aspose.slides/ipicturefillformat/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

ピクチャーフィルスタイルを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDpi()](#getDpi--) | 画像の塗りつぶしに使用される DPI を取得または設定します。 |
| [setDpi(int value)](#setDpi-int-) | 画像の塗りつぶしに使用される DPI を取得または設定します。 |
| [getPictureFillMode()](#getPictureFillMode--) | ピクチャーフィルモードを取得または設定します。 |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | ピクチャーフィルモードを取得または設定します。 |
| [getPicture()](#getPicture--) | ピクチャーを取得します。 |
| [getCropLeft()](#getCropLeft--) | 画像の実際の幅に対するパーセンテージで、左側が切り取られた部分の割合を取得または設定します。 |
| [setCropLeft(float value)](#setCropLeft-float-) | 画像の実際の幅に対するパーセンテージで、左側が切り取られた部分の割合を取得または設定します。 |
| [getCropTop()](#getCropTop--) | 画像の実際の高さに対するパーセンテージで、上側が切り取られた部分の割合を取得または設定します。 |
| [setCropTop(float value)](#setCropTop-float-) | 画像の実際の高さに対するパーセンテージで、上側が切り取られた部分の割合を取得または設定します。 |
| [getCropRight()](#getCropRight--) | 画像の実際の幅に対するパーセンテージで、右側が切り取られた部分の割合を取得または設定します。 |
| [setCropRight(float value)](#setCropRight-float-) | 画像の実際の幅に対するパーセンテージで、右側が切り取られた部分の割合を取得または設定します。 |
| [getCropBottom()](#getCropBottom--) | 画像の実際の高さに対するパーセンテージで、下側が切り取られた部分の割合を取得または設定します。 |
| [setCropBottom(float value)](#setCropBottom-float-) | 画像の実際の高さに対するパーセンテージで、下側が切り取られた部分の割合を取得または設定します。 |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義される塗りつぶし矩形の左端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。 |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義される塗りつぶし矩形の左端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。 |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義される塗りつぶし矩形の上端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。 |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義される塗りつぶし矩形の上端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。 |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義される塗りつぶし矩形の右端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。 |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義される塗りつぶし矩形の右端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。 |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義される塗りつぶし矩形の下端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。 |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義される塗りつぶし矩形の下端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。 |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 塗りつぶし画像の切り取られた領域を削除します。 |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | シェイプのサイズと指定された解像度に基づいて画像サイズを縮小し、圧縮します。 |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | シェイプのサイズと指定された解像度に基づいて画像サイズを縮小し、圧縮します。 |
| [getTileOffsetX()](#getTileOffsetX--) | シェイプの原点からポイント単位でテクスチャの水平オフセットを取得または設定します。 |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | シェイプの原点からポイント単位でテクスチャの水平オフセットを取得または設定します。 |
| [getTileOffsetY()](#getTileOffsetY--) | シェイプの原点からポイント単位でテクスチャの垂直オフセットを取得または設定します。 |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | シェイプの原点からポイント単位でテクスチャの垂直オフセットを取得または設定します。 |
| [getTileScaleX()](#getTileScaleX--) | テクスチャ塗りつぶしの水平スケールをパーセンテージで取得または設定します。 |
| [setTileScaleX(float value)](#setTileScaleX-float-) | テクスチャ塗りつぶしの水平スケールをパーセンテージで取得または設定します。 |
| [getTileScaleY()](#getTileScaleY--) | テクスチャ塗りつぶしの垂直スケールをパーセンテージで取得または設定します。 |
| [setTileScaleY(float value)](#setTileScaleY-float-) | テクスチャ塗りつぶしの垂直スケールをパーセンテージで取得または設定します。 |
| [getTileAlignment()](#getTileAlignment--) | テクスチャがシェイプ内でどのように配置されるかを取得または設定します。 |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | テクスチャがシェイプ内でどのように配置されるかを取得または設定します。 |
| [getTileFlip()](#getTileFlip--) | テクスチャタイルを水平、垂直、または両方の軸で反転させます。 |
| [setTileFlip(int value)](#setTileFlip-int-) | テクスチャタイルを水平、垂直、または両方の軸で反転させます。 |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

画像の塗りつぶしに使用される DPI を取得または設定します。読み書き可能な int。

**戻り値:**  
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

画像の塗りつぶしに使用される DPI を取得または設定します。読み書き可能な int。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

ピクチャーフィルモードを取得または設定します。読み書き可能 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**戻り値:**  
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

ピクチャーフィルモードを取得または設定します。読み書き可能 [PictureFillMode](../../com.aspose.slides/picturefillmode)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

ピクチャーを取得します。読み取り専用 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**戻り値:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

画像の実際の幅に対するパーセンテージで、左側が切り取られた部分の割合を取得または設定します。読み書き可能な float。

**戻り値:**  
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

画像の実際の幅に対するパーセンテージで、左側が切り取られた部分の割合を取得または設定します。読み書き可能な float。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

画像の実際の高さに対するパーセンテージで、上側が切り取られた部分の割合を取得または設定します。読み書き可能な float。

**戻り値:**  
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

画像の実際の高さに対するパーセンテージで、上側が切り取られた部分の割合を取得または設定します。読み書き可能な float。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

画像の実際の幅に対するパーセンテージで、右側が切り取られた部分の割合を取得または設定します。読み書き可能な float。

**戻り値:**  
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

画像の実際の幅に対するパーセンテージで、右側が切り取られた部分の割合を取得または設定します。読み書き可能な float。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

画像の実際の高さに対するパーセンテージで、下側が切り取られた部分の割合を取得または設定します。読み書き可能な float。

**戻り値:**  
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

画像の実際の高さに対するパーセンテージで、下側が切り取られた部分の割合を取得または設定します。読み書き可能な float。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義される塗りつぶし矩形の左端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。読み書き可能な float。

**戻り値:**  
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

シェイプのバウンディングボックスの左端からのパーセンテージオフセットで定義される塗りつぶし矩形の左端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。読み書き可能な float。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義される塗りつぶし矩形の上端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。読み書き可能な float。

**戻り値:**  
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

シェイプのバウンディングボックスの上端からのパーセンテージオフセットで定義される塗りつぶし矩形の上端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。読み書き可能な float。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義される塗りつぶし矩形の右端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。読み書き可能な float。

**戻り値:**  
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

シェイプのバウンディングボックスの右端からのパーセンテージオフセットで定義される塗りつぶし矩形の右端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。読み書き可能な float。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義される塗りつぶし矩形の下端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。読み書き可能な float。

**戻り値:**  
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

シェイプのバウンディングボックスの下端からのパーセンテージオフセットで定義される塗りつぶし矩形の下端を取得または設定します。正のパーセンテージはインセット、負のパーセンテージはアウトセットを表します。読み書き可能な float。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

塗りつぶし画像の切り取られた領域を削除します。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // PictureFrame を取得します
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // PictureFrame の画像の切り抜かれた領域を削除します
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**戻り値:**  
[IPPImage](../../com.aspose.slides/ippimage) - 切り取られた画像、または切り取りが不要な場合は元の画像。

--------------------

このメソッドは、WMF/EMF メタファイルをラスタ PNG 画像に変換し、同時に切り取ります。

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

シェイプのサイズと指定された解像度に基づいて画像サイズを縮小し、圧縮します。必要に応じて切り取られた領域も削除します。

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` メソッドは、ターゲット解像度を設定し、切り取られた領域を削除することで、プレゼンテーション内の画像サイズを縮小します：  
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
> 以下の例は、```
> CompressImage
> ```
 メソッドを使用して、ターゲット解像度を設定し、切り取られた領域を削除することで、プレゼンテーション内の画像サイズを縮小する方法を示します：  
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
**Returns:
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

デフォルトは [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft)です。

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

デフォルトは [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip) です。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |