---
title: HtmlOptions
second_title: Aspose.Slides için Java API Referansı
description: HTML dışa aktarma seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/htmloptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

HTML dışa aktarma seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Yeni bir HtmlOptions nesnesi oluşturur ve geri çağırmayı belirtir. |
| [HtmlOptions()](#HtmlOptions--) | Tek HTML dosyasına kaydetmek için yeni bir HtmlOptions nesnesi oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada konumlandırıldığı modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada konumlandırıldığı modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML şablonunu döndürür veya ayarlar. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML şablonunu döndürür veya ayarlar. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Slayt görüntü formatı seçeneklerini döndürür veya ayarlar. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Slayt görüntü formatı seçeneklerini döndürür veya ayarlar. |
| [getJpegQuality()](#getJpegQuality--) | PDF belgesi içindeki JPEG görüntülerin kalitesini belirleyen bir değeri döndürür veya ayarlar. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF belgesi içindeki JPEG görüntülerin kalitesini belirleyen bir değeri döndürür veya ayarlar. |
| [getPicturesCompression()](#getPicturesCompression--) | Resim sıkıştırma seviyesini temsil eder |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Resim sıkıştırma seviyesini temsil eder |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını gösteren bir boolean bayrağı. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını gösteren bir boolean bayrağı. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True to exclude width and height attributes from svg container - that will make layout responsive. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True to exclude width and height attributes from svg container - that will make layout responsive. |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Yeni bir HtmlOptions nesnesi oluşturur ve geri çağırmayı belirtir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Kaydetme projesini kontrol eden geri çağırma nesnesi. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Tek HTML dosyasına kaydetmek için yeni bir HtmlOptions nesnesi oluşturur.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunumu dışa aktarırken slaytların sayfada konumlandırıldığı modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Sunumu dışa aktarırken slaytların sayfada konumlandırıldığı modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Yalnızca okuma [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan değer false.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan değer false.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

HTML şablonunu döndürür veya ayarlar. Okuma/Yazma [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Döndürür:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

HTML şablonunu döndürür veya ayarlar. Okuma/Yazma [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. true olarak ayarlandığında, ligatürler render çıktısında devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanır.

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

Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. true olarak ayarlandığında, ligatürler render çıktısında devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanır.

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

Slayt görüntü formatı seçeneklerini döndürür veya ayarlar. Okuma/Yazma [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Döndürür:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Slayt görüntü formatı seçeneklerini döndürür veya ayarlar. Okuma/Yazma [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF belgesi içindeki JPEG görüntülerin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okuma/Yazma byte.

--------------------

Yalnızca bir belge JPEG görüntüler içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken bir belgede bulunan görüntülerin kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kalite ancak en yüksek sıkıştırma, 100 en yüksek kalite ancak en düşük sıkıştırma anlamına gelir.

Varsayılan değer **95**'tir.

**Döndürür:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF belgesi içindeki JPEG görüntülerin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okuma/Yazma byte.

--------------------

Yalnızca bir belge JPEG görüntüler içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken bir belgede bulunan görüntülerin kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kalite ancak en yüksek sıkıştırma, 100 en yüksek kalite ancak en düşük sıkıştırma anlamına gelir.

Varsayılan değer **95**'tir.

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

Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını gösteren bir boolean bayrağı. true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir)

**Döndürür:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını gösteren bir boolean bayrağı. true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir)

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |