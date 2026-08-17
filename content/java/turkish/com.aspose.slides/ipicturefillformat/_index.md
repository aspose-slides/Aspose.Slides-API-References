---
title: IPictureFillFormat
second_title: Aspose.Slides için Java API Referansı
description: Bir resim dolgu stilini temsil eder.
type: docs
url: /tr/com.aspose.slides/ipicturefillformat/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Bir resim dolgu stilini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDpi()](#getDpi--) | Resmi doldurmak için kullanılan dpi değerini döndürür veya ayarlar. |
| [setDpi(int value)](#setDpi-int-) | Resmi doldurmak için kullanılan dpi değerini döndürür veya ayarlar. |
| [getPictureFillMode()](#getPictureFillMode--) | Resim dolgu modunu döndürür veya ayarlar. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Resim dolgu modunu döndürür veya ayarlar. |
| [getPicture()](#getPicture--) | Resmi döndürür. |
| [getCropLeft()](#getCropLeft--) | Gerçek görüntü genişliğinin sol tarafından kırpılan yüzde oranını döndürür veya ayarlar. |
| [setCropLeft(float value)](#setCropLeft-float-) | Gerçek görüntü genişliğinin sol tarafından kırpılan yüzde oranını döndürür veya ayarlar. |
| [getCropTop()](#getCropTop--) | Gerçek görüntü yüksekliğinin üst tarafından kırpılan yüzde oranını döndürür veya ayarlar. |
| [setCropTop(float value)](#setCropTop-float-) | Gerçek görüntü yüksekliğinin üst tarafından kırpılan yüzde oranını döndürür veya ayarlar. |
| [getCropRight()](#getCropRight--) | Gerçek görüntü genişliğinin sağ tarafından kırpılan yüzde oranını döndürür veya ayarlar. |
| [setCropRight(float value)](#setCropRight-float-) | Gerçek görüntü genişliğinin sağ tarafından kırpılan yüzde oranını döndürür veya ayarlar. |
| [getCropBottom()](#getCropBottom--) | Gerçek görüntü yüksekliğinin alt tarafından kırpılan yüzde oranını döndürür veya ayarlar. |
| [setCropBottom(float value)](#setCropBottom-float-) | Gerçek görüntü yüksekliğinin alt tarafından kırpılan yüzde oranını döndürür veya ayarlar. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sol kenarını döndürür veya ayarlar. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sol kenarını döndürür veya ayarlar. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin üst kenarını döndürür veya ayarlar. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin üst kenarını döndürür veya ayarlar. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür veya ayarlar. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür veya ayarlar. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin alt kenarını döndürür veya ayarlar. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin alt kenarını döndürür veya ayarlar. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Doldurma resminin kırpılmış alanlarını siler. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Görüntüyü şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek sıkıştırır. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Görüntüyü şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek sıkıştırır. |
| [getTileOffsetX()](#getTileOffsetX--) | Doku kaynağının şeklin orijininden yatay ofsetini nokta cinsinden döndürür veya ayarlar. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Doku kaynağının şeklin orijininden yatay ofsetini nokta cinsinden döndürür veya ayarlar. |
| [getTileOffsetY()](#getTileOffsetY--) | Doku kaynağının şeklin orijininden dikey ofsetini nokta cinsinden döndürür veya ayarlar. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Doku kaynağının şeklin orijininden dikey ofsetini nokta cinsinden döndürür veya ayarlar. |
| [getTileScaleX()](#getTileScaleX--) | Doku dolgu için yatay ölçeği yüzde olarak döndürür veya ayarlar. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Doku dolgu için yatay ölçeği yüzde olarak döndürür veya ayarlar. |
| [getTileScaleY()](#getTileScaleY--) | Doku dolgu için dikey ölçeği yüzde olarak döndürür veya ayarlar. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Doku dolgu için dikey ölçeği yüzde olarak döndürür veya ayarlar. |
| [getTileAlignment()](#getTileAlignment--) | Dokunun şekil içinde nasıl hizalandığını döndürür veya ayarlar. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Dokunun şekil içinde nasıl hizalandığını döndürür veya ayarlar. |
| [getTileFlip()](#getTileFlip--) | Doku karosunu yatay, dikey veya her iki eksende tersine çevirir. |
| [setTileFlip(int value)](#setTileFlip-int-) | Doku karosunu yatay, dikey veya her iki eksende tersine çevirir. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Resmi doldurmak için kullanılan dpi değerini döndürür veya ayarlar. **Okunur/Yazılır** int.

**Döndürür:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Resmi doldurmak için kullanılan dpi değerini döndürür veya ayarlar. **Okunur/Yazılır** int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Resim dolgu modunu döndürür veya ayarlar. **Okunur/Yazılır** [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Döndürür:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Resim dolgu modunu döndürür veya ayarlar. **Okunur/Yazılır** [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Resmi döndürür. **Salt Okunur** [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Döndürür:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Gerçek görüntü genişliğinin sol tarafından kırpılan yüzde oranını döndürür veya ayarlar. **Okunur/Yazılır** float.

**Döndürür:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Gerçek görüntü genişliğinin sol tarafından kırpılan yüzde oranını döndürür veya ayarlar. **Okunur/Yazılır** float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Gerçek görüntü yüksekliğinin üst tarafından kırpılan yüzde oranını döndürür veya ayarlar. **Okunur/Yazılır** float.

**Döndürür:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Gerçek görüntü yüksekliğinin üst tarafından kırpılan yüzde oranını döndürür veya ayarlar. **Okunur/Yazılır** float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Gerçek görüntü genişliğinin sağ tarafından kırpılan yüzde oranını döndürür veya ayarlar. **Okunur/Yazılır** float.

**Döndürür:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Gerçek görüntü genişliğinin sağ tarafından kırpılan yüzde oranını döndürür veya ayarlar. **Okunur/Yazılır** float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Gerçek görüntü yüksekliğinin alt tarafından kırpılan yüzde oranını döndürür veya ayarlar. **Okunur/Yazılır** float.

**Döndürür:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Gerçek görüntü yüksekliğinin alt tarafından kırpılan yüzde oranını döndürür veya ayarlar. **Okunur/Yazılır** float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sol kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **Okunur/Yazılır** float.

**Döndürür:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Şeklin sınırlayıcı kutusunun sol kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sol kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **Okunur/Yazılır** float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin üst kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **Okunur/Yazılır** float.

**Döndürür:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Şeklin sınırlayıcı kutusunun üst kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin üst kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **Okunur/Yazılır** float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **Okunur/Yazılır** float.

**Döndürür:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Şeklin sınırlayıcı kutusunun sağ kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **Okunur/Yazılır** float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin alt kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **Okunur/Yazılır** float.

**Döndürür:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Şeklin sınırlayıcı kutusunun alt kenarından yüzde ofset ile tanımlanan doldurma dikdörtgeninin alt kenarını döndürür veya ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **Okunur/Yazılır** float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Doldurma resminin kırpılmış alanlarını siler.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Resim Çerçevesini alır
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Resim Çerçevesinin görüntüsünün kırpılmış alanlarını siler
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Kırpılmış görüntü veya kırpma gerekli değilse orijinal görüntü.

--------------------

Bu yöntem WMF/EMF metafilelerini kırparak raster PNG görüntüsüne dönüştürür.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Görüntüyü şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` yöntemi, bir sunumdaki görüntünün hedef çözünürlüğünü ayarlayarak ve kırpılmış alanları kaldırarak boyutunu küçültür:
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
> Aşağıdaki örnek, ```
> CompressImage
> ``` yöntemini kullanarak bir sunumdaki görüntünün hedef çözünürlüğünü ayarlayıp kırpılmış alanları kaldırmayı gösterir:
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

**Parametreler:**
| Parametre | Tür | Açıklama |
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