---
title: IPictureFillFormat
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir resim dolgu stilini temsil eder.
type: docs
url: /tr/com.aspose.slides/ipicturefillformat/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Bir resim doldurma stilini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDpi()](#getDpi--) | Resmi doldurmak için kullanılan dpi değerini alır veya ayarlar. |
| [setDpi(int value)](#setDpi-int-) | Resmi doldurmak için kullanılan dpi değerini alır veya ayarlar. |
| [getPictureFillMode()](#getPictureFillMode--) | Resim doldurma modunu alır veya ayarlar. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Resim doldurma modunu alır veya ayarlar. |
| [getPicture()](#getPicture--) | Resmi döndürür. |
| [getCropLeft()](#getCropLeft--) | Resmin gerçek genişliğinin sol tarafından kırpılan yüzde miktarını alır veya ayarlar. |
| [setCropLeft(float value)](#setCropLeft-float-) | Resmin gerçek genişliğinin sol tarafından kırpılan yüzde miktarını alır veya ayarlar. |
| [getCropTop()](#getCropTop--) | Resmin gerçek yüksekliğinin üst kısmından kırpılan yüzde miktarını alır veya ayarlar. |
| [setCropTop(float value)](#setCropTop-float-) | Resmin gerçek yüksekliğinin üst kısmından kırpılan yüzde miktarını alır veya ayarlar. |
| [getCropRight()](#getCropRight--) | Resmin gerçek genişliğinin sağ tarafından kırpılan yüzde miktarını alır veya ayarlar. |
| [setCropRight(float value)](#setCropRight-float-) | Resmin gerçek genişliğinin sağ tarafından kırpılan yüzde miktarını alır veya ayarlar. |
| [getCropBottom()](#getCropBottom--) | Resmin gerçek yüksekliğinin alt kısmından kırpılan yüzde miktarını alır veya ayarlar. |
| [setCropBottom(float value)](#setCropBottom-float-) | Resmin gerçek yüksekliğinin alt kısmından kırpılan yüzde miktarını alır veya ayarlar. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Şeklin sınırlayıcı kutusunun sol kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sol kenarını alır veya ayarlar. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Şeklin sınırlayıcı kutusunun sol kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sol kenarını alır veya ayarlar. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Şeklin sınırlayıcı kutusunun üst kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin üst kenarını alır veya ayarlar. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Şeklin sınırlayıcı kutusunun üst kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin üst kenarını alır veya ayarlar. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sağ kenarını alır veya ayarlar. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sağ kenarını alır veya ayarlar. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Şeklin sınırlayıcı kutusunun alt kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin alt kenarını alır veya ayarlar. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Şeklin sınırlayıcı kutusunun alt kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin alt kenarını alır veya ayarlar. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Doldurma resmindeki kırpılmış alanları siler. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu azaltarak sıkıştırır. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu azaltarak sıkıştırır. |
| [getTileOffsetX()](#getTileOffsetX--) | Doku kaynağının şeklin orijinden yatay offsetini nokta cinsinden alır veya ayarlar. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Doku kaynağının şeklin orijinden yatay offsetini nokta cinsinden alır veya ayarlar. |
| [getTileOffsetY()](#getTileOffsetY--) | Doku kaynağının şeklin orijinden düşey offsetini nokta cinsinden alır veya ayarlar. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Doku kaynağının şeklin orijinden düşey offsetini nokta cinsinden alır veya ayarlar. |
| [getTileScaleX()](#getTileScaleX--) | Doku doldurma için yatay ölçeği yüzde olarak alır veya ayarlar. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Doku doldurma için yatay ölçeği yüzde olarak alır veya ayarlar. |
| [getTileScaleY()](#getTileScaleY--) | Doku doldurma için düşey ölçeği yüzde olarak alır veya ayarlar. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Doku doldurma için düşey ölçeği yüzde olarak alır veya ayarlar. |
| [getTileAlignment()](#getTileAlignment--) | Dokunun şekil içinde nasıl hizalandığını alır veya ayarlar. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Dokunun şekil içinde nasıl hizalandığını alır veya ayarlar. |
| [getTileFlip()](#getTileFlip--) | Doku karosunu yatay, düşey ya da her iki eksen etrafında ters çevirir. |
| [setTileFlip(int value)](#setTileFlip-int-) | Doku karosunu yatay, düşey ya da her iki eksen etrafında ters çevirir. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Resmi doldurmak için kullanılan dpi değerini alır veya ayarlar. Okunur/yazılır int.

**Döndürür:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Resmi doldurmak için kullanılan dpi değerini alır veya ayarlar. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Resim doldurma modunu alır veya ayarlar. Okunur/yazılır [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Döndürür:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Resim doldurma modunu alır veya ayarlar. Okunur/yazılır [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Resmi döndürür. Okunur [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Döndürür:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Resmin gerçek genişliğinin sol tarafından kırpılan yüzde miktarını alır veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Resmin gerçek genişliğinin sol tarafından kırpılan yüzde miktarını alır veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Resmin gerçek yüksekliğinin üst kısmından kırpılan yüzde miktarını alır veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Resmin gerçek yüksekliğinin üst kısmından kırpılan yüzde miktarını alır veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Resmin gerçek genişliğinin sağ tarafından kırpılan yüzde miktarını alır veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Resmin gerçek genişliğinin sağ tarafından kırpılan yüzde miktarını alır veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Resmin gerçek yüksekliğinin alt kısmından kırpılan yüzde miktarını alır veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Resmin gerçek yüksekliğinin alt kısmından kırpılan yüzde miktarını alır veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Şeklin sınırlayıcı kutusunun sol kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sol kenarını alır veya ayarlar. Pozitif yüzde iç içe girme, negatif yüzde dışa çıkma anlamına gelir. Okunur/yazılır float.

**Döndürür:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Şeklin sınırlayıcı kutusunun sol kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sol kenarını alır veya ayarlar. Pozitif yüzde iç içe girme, negatif yüzde dışa çıkma anlamına gelir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Şeklin sınırlayıcı kutusunun üst kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin üst kenarını alır veya ayarlar. Pozitif yüzde iç içe girme, negatif yüzde dışa çıkma anlamına gelir. Okunur/yazılır float.

**Döndürür:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Şeklin sınırlayıcı kutusunun üst kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin üst kenarını alır veya ayarlar. Pozitif yüzde iç içe girme, negatif yüzde dışa çıkma anlamına gelir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Şeklin sınırlayıcı kutusunun sağ kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sağ kenarını alır veya ayarlar. Pozitif yüzde iç içe girme, negatif yüzde dışa çıkma anlamına gelir. Okunur/yazılır float.

**Döndürür:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Şeklin sınırlayıcı kutusunun sağ kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sağ kenarını alır veya ayarlar. Pozitif yüzde iç içe girme, negatif yüzde dışa çıkma anlamına gelir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Şeklin sınırlayıcı kutusunun alt kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin alt kenarını alır veya ayarlar. Pozitif yüzde iç içe girme, negatif yüzde dışa çıkma anlamına gelir. Okunur/yazılır float.

**Döndürür:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Şeklin sınırlayıcı kutusunun alt kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin alt kenarını alır veya ayarlar. Pozitif yüzde iç içe girme, negatif yüzde dışa çıkma anlamına gelir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Doldurma resmindeki kırpılmış alanları siler.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // PictureFrame'i alır
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // PictureFrame görselinin kırpılmış alanlarını siler
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Kırpılmış görüntü veya kırpma gerekmiyorsa orijinal görüntü.

--------------------

Bu yöntem WMF/EMF metafile’larını raster PNG görüntüsüne dönüştürürken kırpar.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu azaltarak sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` yöntemi bir sunumdaki görüntünün boyutunu hedef çözünürlük ayarlayarak ve kırpılmış alanları kaldırarak azaltır:
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
> The following example demonstrates how to use the ```
> CompressImage
> ```
 method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
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

Varsayılan [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |