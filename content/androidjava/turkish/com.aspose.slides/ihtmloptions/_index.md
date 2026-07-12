---
title: IHtmlOptions
second_title: Aspose.Slides for Android için Java API Referansı
description: HTML dışa aktarma seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ihtmloptions/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

HTML dışa aktarma seçeneklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | HTML şablonunu alır veya ayarlar. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | HTML şablonunu alır veya ayarlar. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Slayt görüntü formatı seçeneklerini alır veya ayarlar. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Slayt görüntü formatı seçeneklerini alır veya ayarlar. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getJpegQuality()](#getJpegQuality--) | PDF belgesi içindeki JPEG görüntülerin kalitesini belirleyen bir değeri alır veya ayarlar. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF belgesi içindeki JPEG görüntülerin kalitesini belirleyen bir değeri alır veya ayarlar. |
| [getPicturesCompression()](#getPicturesCompression--) | Resim sıkıştırma seviyesini temsil eder Okuma/yazma [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Resim sıkıştırma seviyesini temsil eder Okuma/yazma [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Kırpılmış bölümlerin belge içinde kalıp kalmayacağını gösteren bir boolean işareti. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Kırpılmış bölümlerin belge içinde kalıp kalmayacağını gösteren bir boolean işareti. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | SVG kapsayıcısında genişlik ve yükseklik özniteliklerini dışlamak için true - bu, düzeni duyarlı hâle getirir. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | SVG kapsayıcısında genişlik ve yükseklik özniteliklerini dışlamak için true - bu, düzeni duyarlı hâle getirir. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Ligaturalar kullanılmadan metnin render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Ligaturalar kullanılmadan metnin render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

HTML şablonunu alır veya ayarlar. Okuma/yazma [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Döndürür:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

HTML şablonunu alır veya ayarlar. Okuma/yazma [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Slayt görüntü formatı seçeneklerini alır veya ayarlar. Okuma/yazma [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Döndürür:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Slayt görüntü formatı seçeneklerini alır veya ayarlar. Okuma/yazma [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değeri false'tur.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değeri false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Kalite belirleyen bir değeri alır veya ayarlar. Okuma/yazma byte.

--------------------

Yalnızca bir belge JPEG görüntüleri içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken belgedeki görüntülerin kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kaliteyi ama en yüksek sıkıştırmayı, 100 ise en yüksek kaliteyi ama en düşük sıkıştırmayı gösterir.

Varsayılan değer **95**'tir.

**Döndürür:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Kalite belirleyen bir değeri alır veya ayarlar. Okuma/yazma byte.

--------------------

Yalnızca bir belge JPEG görüntüleri içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken belgedeki görüntülerin kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kaliteyi ama en yüksek sıkıştırmayı, 100 ise en yüksek kaliteyi ama en düşük sıkıştırmayı gösterir.

Varsayılan değer **95**'tir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Resim sıkıştırma seviyesini temsil eder Okuma/yazma [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Döndürür:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Resim sıkıştırma seviyesini temsil eder Okuma/yazma [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Kırpılmış bölümlerin belge içinde kalıp kalmayacağını gösteren bir boolean işareti. true ise kırpılmış bölümler kaldırılır, false ise belgeye serileştirilir (bu dosyanın daha büyük olmasına yol açabilir) Okuma/yazma boolean.

**Döndürür:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Kırpılmış bölümlerin belge içinde kalıp kalmayacağını gösteren bir boolean işareti. true ise kırpılmış bölümler kaldırılır, false ise belgeye serileştirilir (bu dosyanın daha büyük olmasına yol açabilir) Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

SVG kapsayıcısında genişlik ve yükseklik özniteliklerini dışlamak için true - bu, düzeni duyarlı hâle getirir. False - aksi takdirde. Okuma/yazma boolean.

**Döndürür:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

SVG kapsayıcısında genişlik ve yükseklik özniteliklerini dışlamak için true - bu, düzeni duyarlı hâle getirir. False - aksi takdirde. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Ligaturalar kullanılmadan metnin render edilip edilmediğini gösteren bir değeri alır veya ayarlar. true olarak ayarlandığında, render edilen çıktıda ligaturalar devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.

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
public abstract void setDisableFontLigatures(boolean value)
```

Ligaturalar kullanılmadan metnin render edilip edilmediğini gösteren bir değeri alır veya ayarlar. true olarak ayarlandığında, render edilen çıktıda ligaturalar devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.

--------------------

> ```
> Örnek:
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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Örnek:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Örnek:
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
public abstract IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Sadece okuma [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)