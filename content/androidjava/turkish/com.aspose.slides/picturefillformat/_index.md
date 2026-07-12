---
title: PictureFillFormat
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Bir resim doldurma stilini temsil eder.
type: docs
url: /tr/com.aspose.slides/picturefillformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Bir resim dolgu stilini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Bir resmi doldurmak için kullanılan dpi'yi alır veya ayarlar. |
| [setDpi(int value)](#setDpi-int-) | Bir resmi doldurmak için kullanılan dpi'yi alır veya ayarlar. |
| [getPictureFillMode()](#getPictureFillMode--) | Resim dolgu modunu alır veya ayarlar. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Resim dolgu modunu alır veya ayarlar. |
| [getPicture()](#getPicture--) | Resmi alır. |
| [getCropLeft()](#getCropLeft--) | Resmin sol tarafından kırpılan gerçek görüntü genişliğinin yüzde oranını alır veya ayarlar. |
| [setCropLeft(float value)](#setCropLeft-float-) | Resmin sol tarafından kırpılan gerçek görüntü genişliğinin yüzde oranını alır veya ayarlar. |
| [getCropTop()](#getCropTop--) | Resmin üstünden kırpılan gerçek görüntü yüksekliğinin yüzde oranını alır veya ayarlar. |
| [setCropTop(float value)](#setCropTop-float-) | Resmin üstünden kırpılan gerçek görüntü yüksekliğinin yüzde oranını alır veya ayarlar. |
| [getCropRight()](#getCropRight--) | Resmin sağ tarafından kırpılan gerçek görüntü genişliğinin yüzde oranını alır veya ayarlar. |
| [setCropRight(float value)](#setCropRight-float-) | Resmin sağ tarafından kırpılan gerçek görüntü genişliğinin yüzde oranını alır veya ayarlar. |
| [getCropBottom()](#getCropBottom--) | Resmin altından kırpılan gerçek görüntü yüksekliğinin yüzde oranını alır veya ayarlar. |
| [setCropBottom(float value)](#setCropBottom-float-) | Resmin altından kırpılan gerçek görüntü yüksekliğinin yüzde oranını alır veya ayarlar. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Doldurma resmindeki kırpılmış alanları sil. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek resmi sıkıştırır. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek resmi sıkıştırır. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin sol kenarını alır veya ayarlar. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin sol kenarını alır veya ayarlar. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin üst kenarını alır veya ayarlar. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin üst kenarını alır veya ayarlar. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin sağ kenarını alır veya ayarlar. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin sağ kenarını alır veya ayarlar. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin alt kenarını alır veya ayarlar. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin alt kenarını alır veya ayarlar. |
| [getTileOffsetX()](#getTileOffsetX--) | Dokunun şeklin orijinalinden nokta cinsinden yatay ofsetini alır veya ayarlar. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Dokunun şeklin orijinalinden nokta cinsinden yatay ofsetini alır veya ayarlar. |
| [getTileOffsetY()](#getTileOffsetY--) | Dokunun şeklin orijinalinden nokta cinsinden dikey ofsetini alır veya ayarlar. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Dokunun şeklin orijinalinden nokta cinsinden dikey ofsetini alır veya ayarlar. |
| [getTileScaleX()](#getTileScaleX--) | Dokunun yatay ölçeğini yüzde olarak alır veya ayarlar. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Dokunun yatay ölçeğini yüzde olarak alır veya ayarlar. |
| [getTileScaleY()](#getTileScaleY--) | Dokunun dikey ölçeğini yüzde olarak alır veya ayarlar. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Dokunun dikey ölçeğini yüzde olarak alır veya ayarlar. |
| [getTileAlignment()](#getTileAlignment--) | Dokunun şekil içinde nasıl hizalandığını alır veya ayarlar. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Dokunun şekil içinde nasıl hizalandığını alır veya ayarlar. |
| [getTileFlip()](#getTileFlip--) | Dokunun karolarını yatay, dikey veya her iki eksende çevirir. |
| [setTileFlip(int value)](#setTileFlip-int-) | Dokunun karolarını yatay, dikey veya her iki eksende çevirir. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur long.

**Döndürür:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Bir resmi doldurmak için kullanılan dpi'yi alır veya ayarlar. Okunur/yazılır  int .

**Döndürür:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Bir resmi doldurmak için kullanılan dpi'yi alır veya ayarlar. Okunur/yazılır  int .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Resim dolgu modunu alır veya ayarlar. Okunur/yazılır [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Döndürür:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Resim dolgu modunu alır veya ayarlar. Okunur/yazılır [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Resmi alır. Salt okunur [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Döndürür:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Resmin sol tarafından kırpılan gerçek görüntü genişliğinin yüzde oranını alır veya ayarlar. Okunur/yazılır  float .

**Döndürür:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Resmin sol tarafından kırpılan gerçek görüntü genişliğinin yüzde oranını alır veya ayarlar. Okunur/yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Resmin üstünden kırpılan gerçek görüntü yüksekliğinin yüzde oranını alır veya ayarlar. Okunur/yazılır  float .

**Döndürür:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Resmin üstünden kırpılan gerçek görüntü yüksekliğinin yüzde oranını alır veya ayarlar. Okunur/yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Resmin sağ tarafından kırpılan gerçek görüntü genişliğinin yüzde oranını alır veya ayarlar. Okunur/yazılır  float .

**Döndürür:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Resmin sağ tarafından kırpılan gerçek görüntü genişliğinin yüzde oranını alır veya ayarlar. Okunur/yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Resmin altından kırpılan gerçek görüntü yüksekliğinin yüzde oranını alır veya ayarlar. Okunur/yazılır  float .

**Döndürür:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Resmin altından kırpılan gerçek görüntü yüksekliğinin yüzde oranını alır veya ayarlar. Okunur/yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Doldurma resmindeki kırpılmış alanları sil.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // PictureFrame'i alır
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // PictureFrame görüntüsünün kırpılmış alanlarını siler
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Kırpılmış görüntü veya kırpma gerekmediğinde orijinal görüntü.

--------------------

Bu yöntem, WMF/EMF metafile'larını kırparak raster PNG görüntüsüne dönüştürür.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek resmi sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` yöntemi, bir sunumdaki görüntünün boyutunu hedef çözünürlük belirleyerek ve kırpılmış alanları kaldırarak küçültür:
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
> Aşağıdaki örnek, ```
> CompressImage
> ```
 yöntemini kullanarak bir sunumdaki görüntünün boyutunu hedef çözünürlük belirleyip kırpılmış alanları kaldırarak nasıl küçülteceğini gösterir:
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

Dolgu dikdörtgeninin üst kenarını, şeklin sınırlayıcı kutusunun üst kenarından yüzde ofsetle tanımlanan değeri alır veya ayarlar. Pozitif bir yüzde içe doğru itme, negatif bir yüzde ise dışa doğru itme belirtir. Read/write  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
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

Alt kenarı, şeklin sınırlayıcı kutusunun alt kenarından yüzde ofsetle tanımlanan dolgu dikdörtgeninin alt kenarını alır veya ayarlar. Pozitif yüzde içe doğru itme, negatif yüzde ise dışa doğru itme belirtir. Okunur/yazılır  float .

**Döndürür:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```

Dolgu dikdörtgeninin alt kenarını, şeklin sınırlayıcı kutusunun alt kenarından yüzde ofsetle tanımlanan değeri alır veya ayarlar. Pozitif bir yüzde içe doğru itme, negatif bir yüzde ise dışa doğru itme belirtir. Okunur/yazılır  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
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

Returns      
The  
```


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

Varsayılan [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |