---
title: HtmlOptions
second_title: Aspose.Slides for Android için Java API Referansı
description: HTML dışa aktarma seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/htmloptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

HTML dışa aktarma seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Callback belirten yeni bir HtmlOptions nesnesi oluşturur. |
| [HtmlOptions()](#HtmlOptions--) | Tek HTML dosyasına kaydetmek için yeni bir HtmlOptions nesnesi oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML şablonunu alır veya ayarlar. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML şablonunu alır veya ayarlar. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Slayt resim formatı seçeneklerini alır veya ayarlar. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Slayt resim formatı seçeneklerini alır veya ayarlar. |
| [getJpegQuality()](#getJpegQuality--) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri alır veya ayarlar. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri alır veya ayarlar. |
| [getPicturesCompression()](#getPicturesCompression--) | Resim sıkıştırma seviyesini temsil eder |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Resim sıkıştırma seviyesini temsil eder |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean bayrağı. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean bayrağı. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | svg kapsayıcısındaki width ve height özniteliklerini hariç tutmak için true - bu, düzeni duyarlı hâle getirir. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | svg kapsayıcısındaki width ve height özniteliklerini hariç tutmak için true - bu, düzeni duyarlı hâle getirir. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Callback belirten yeni bir HtmlOptions nesnesi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Proje kaydetmeyi kontrol eden geri arama nesnesi. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Tek HTML dosyasına kaydetmek için yeni bir HtmlOptions nesnesi oluşturur.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Salt okunur [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

HTML şablonunu alır veya ayarlar. Okunur/yazılır [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Döndürür:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

HTML şablonunu alır veya ayarlar. Okunur/yazılır [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. true olarak ayarlandığında, render edilen çıktıda ligatürler devre dışı bırakılır. Varsayılan olarak bu özellik false'tur.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. true olarak ayarlandığında, render edilen çıktıda ligatürler devre dışı bırakılır. Varsayılan olarak bu özellik false'tur.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Slayt resim formatı seçeneklerini alır veya ayarlar. Okunur/yazılır [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Döndürür:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Slayt resim formatı seçeneklerini alır veya ayarlar. Okunur/yazılır [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri alır veya ayarlar. Okunur/yazılır byte.

**Döndürür:**
byte

Yalnızca belge JPEG görüntüler içerdiğinde etkilidir.

Bu özelliği, PDF formatında kaydederken belgede bulunan görüntülerin kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişebilir; 0 en düşük kalite ama en yüksek sıkıştırma, 100 en yüksek kalite ama en düşük sıkıştırma anlamına gelir.

Varsayılan değer **95**.

**Döndürür:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri alır veya ayarlar. Okunur/yazılır byte.

Yalnızca belge JPEG görüntüler içerdiğinde etkilidir.

Bu özelliği, PDF formatında kaydederken belgede bulunan görüntülerin kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişebilir; 0 en düşük kalite ama en yüksek sıkıştırma, 100 en yüksek kalite ama en düşük sıkıştırma anlamına gelir.

Varsayılan değer **95**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Resim sıkıştırma seviyesini temsil eder

**Döndürür:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Resim sıkıştırma seviyesini temsil eder

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean bayrağı. true ise kırpılmış bölümler kaldırılır, false ise belge içinde serileştirilir (bu, dosyanın daha büyük olmasına sebep olabilir).

**Döndürür:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean bayrağı. true ise kırpılmış bölümler kaldırılır, false ise belge içinde serileştirilir (bu, dosyanın daha büyük olmasına sebep olabilir).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

svg kapsayıcısındaki width ve height özniteliklerini hariç tutmak için true - bu, düzeni duyarlı hâle getirir. Aksi takdirde false. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

svg kapsayıcısındaki width ve height özniteliklerini hariç tutmak için true - bu, düzeni duyarlı hâle getirir. Aksi takdirde false. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |