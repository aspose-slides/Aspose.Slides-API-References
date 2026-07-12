---
title: ITiffOptions
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/itiffoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Sunumun TIFF formatında kaydedilmesini kontrol eden seçenekler sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImageSize()](#getImageSize--) | Oluşturulan TIFF görüntüsünün boyutunu belirler. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Oluşturulan TIFF görüntüsünün boyutunu belirler. |
| [getDpiX()](#getDpiX--) | Yatay çözünürlüğü inç başına nokta (dpi) olarak belirler. |
| [setDpiX(long value)](#setDpiX-long-) | Yatay çözünürlüğü inç başına nokta (dpi) olarak belirler. |
| [getDpiY()](#getDpiY--) | Dikey çözünürlüğü inç başına nokta (dpi) olarak belirler. |
| [setDpiY(long value)](#setDpiY-long-) | Dikey çözünürlüğü inç başına nokta (dpi) olarak belirler. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. |
| [getCompressionType()](#getCompressionType--) | Sıkıştırma tipini belirler. |
| [setCompressionType(int value)](#setCompressionType-int-) | Sıkıştırma tipini belirler. |
| [getPixelFormat()](#getPixelFormat--) | Oluşturulan görüntüler için piksel biçimini belirler. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Oluşturulan görüntüler için piksel biçimini belirler. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır ya da ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır ya da ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Renkli bir resmi siyah-beyaz bir resme dönüştürmek için algoritmayı belirler. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Renkli bir resmi siyah-beyaz bir resme dönüştürmek için algoritmayı belirler. |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Oluşturulan TIFF görüntüsünün boyutunu belirler. Varsayılan değer 0x0dır; bu, oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir. Okuma/Yazma [Size](../../com.aspose.slides.android/size).

**Döndürür:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Oluşturulan TIFF görüntüsünün boyutunu belirler. Varsayılan değer 0x0dır; bu, oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir. Okuma/Yazma [Size](../../com.aspose.slides.android/size).

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Yatay çözünürlüğü inç başına nokta (dpi) olarak belirler. Okuma/Yazma long.

**Döndürür:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Yatay çözünürlüğü inç başına nokta (dpi) olarak belirler. Okuma/Yazma long.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Dikey çözünürlüğü inç başına nokta (dpi) olarak belirler. Okuma/Yazma long.

**Döndürür:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Dikey çözünürlüğü inç başına nokta (dpi) olarak belirler. Okuma/Yazma long.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan false’dur.

**Döndürür:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan false’dur.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Sıkıştırma tipini belirler. Okuma/Yazma [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Döndürür:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Sıkıştırma tipini belirler. Okuma/Yazma [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Oluşturulan görüntüler için piksel biçimini belirler. Okuma/Yazma [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Döndürür:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Oluşturulan görüntüler için piksel biçimini belirler. Okuma/Yazma [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır ya da ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır ya da ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

Renkli bir resmi siyah-beyaz bir resme dönüştürmek için algoritmayı belirler. Bu seçenek yalnızca CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) veya [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) olarak ayarlandığında uygulanır. Okuma/Yazma [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Varsayılan [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Renkli bir resmi siyah-beyaz bir resme dönüştürmek için algoritmayı belirler. Bu seçenek yalnızca CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) veya [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) olarak ayarlandığında uygulanır. Okuma/Yazma [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Varsayılan [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Sadece okuma [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)