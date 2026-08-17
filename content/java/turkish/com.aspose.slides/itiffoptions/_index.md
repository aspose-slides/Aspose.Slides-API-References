---
title: ITiffOptions
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/itiffoptions/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Bir sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImageSize()](#getImageSize--) | Oluşturulan TIFF görüntüsünün boyutunu belirtir. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Oluşturulan TIFF görüntüsünün boyutunu belirtir. |
| [getDpiX()](#getDpiX--) | Inç başına nokta cinsinden yatay çözünürlüğü belirtir. |
| [setDpiX(long value)](#setDpiX-long-) | Inç başına nokta cinsinden yatay çözünürlüğü belirtir. |
| [getDpiY()](#getDpiY--) | Inç başına nokta cinsinden dikey çözünürlüğü belirtir. |
| [setDpiY(long value)](#setDpiY-long-) | Inç başına nokta cinsinden dikey çözünürlüğü belirtir. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getCompressionType()](#getCompressionType--) | Sıkıştırma türünü belirtir. |
| [setCompressionType(int value)](#setCompressionType-int-) | Sıkıştırma türünü belirtir. |
| [getPixelFormat()](#getPixelFormat--) | Oluşturulan görüntüler için piksel biçimini belirtir. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Oluşturulan görüntüler için piksel biçimini belirtir. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Bir sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Bir sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürmek için algoritmayı belirtir. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürmek için algoritmayı belirtir. |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |

### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dır, bu da oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir. Okuma/yazma java.awt.Dimension.

**Döndürür:**
java.awt.Dimension

### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dır, bu da oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir. Okuma/yazma java.awt.Dimension.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Inç başına nokta cinsinden yatay çözünürlüğü belirtir. Okuma/yazma long.

**Döndürür:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Inç başına nokta cinsinden yatay çözünürlüğü belirtir. Okuma/yazma long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Inç başına nokta cinsinden dikey çözünürlüğü belirtir. Okuma/yazma long.

**Döndürür:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Inç başına nokta cinsinden dikey çözünürlüğü belirtir. Okuma/yazma long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değer false'dur.

**Döndürür:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değer false'dur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Sıkıştırma türünü belirtir. Okuma/yazma [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Döndürür:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Sıkıştırma türünü belirtir. Okuma/yazma [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Oluşturulan görüntüler için piksel biçimini belirtir. Okuma/yazma [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Döndürür:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Oluşturulan görüntüler için piksel biçimini belirtir. Okuma/yazma [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Bir sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
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

Bir sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürmek için algoritmayı belirtir. Bu seçenek yalnızca CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) veya [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) olarak ayarlanmışsa uygulanır. Okuma/yazma [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Varsayılan [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürmek için algoritmayı belirtir. Bu seçenek yalnızca CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) veya [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) olarak ayarlanmışsa uygulanır. Okuma/yazma [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Varsayılan [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Yalnızca okuma [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)