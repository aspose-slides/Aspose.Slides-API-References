---
title: TiffOptions
second_title: Aspose.Slides for Android Java API Referansı
description: Bir sunumun TIFF biçiminde nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/tiffoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Sunumun TIFF formatında kaydedilmesini kontrol eden seçenekler sağlar.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Sunumu temsil eden bir Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Sunumu TIFF belgesine kaydeder
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Sunumu temsil eden bir Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // TiffOptions sınıfını oluşturur
>      TiffOptions opts = new TiffOptions();
>      // Sıkıştırma tipini ayarlar
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Sıkıştırma Türleri
>      // Default - Varsayılan sıkıştırma şemasını (LZW) belirtir.
>      // None - Sıkıştırma olmadığını belirtir.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Derinlik sıkıştırma tipine bağlıdır ve manuel olarak ayarlanamaz.
>      // Çözünürlük birimi her zaman 2'ye eşittir (inç başına nokta)
>      // Görüntü DPI değerlerini ayarlar
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Görüntü Boyutunu Ayarla
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Sunumu belirtilen görüntü boyutuyla TIFF olarak kaydeder
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Sunumu temsil eden bir Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat aşağıdaki değerleri içerir (belgelerden görüldüğü gibi):
>      //Format1bppIndexed; // 1 bit piksel, indeksli.
>      //Format4bppIndexed; // 4 bit piksel, indeksli.
>      //Format8bppIndexed; // 8 bit piksel, indeksli.
>      //Format24bppRgb; // 24 bit piksel, RGB.
>      //Format32bppArgb; // 32 bit piksel, ARGB.
> 
>      // Sunumu belirtilen görüntü boyutuyla TIFF olarak kaydeder
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Varsayılan yapıcı. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getImageSize()](#getImageSize--) | Oluşturulan TIFF görüntüsünün boyutunu belirtir. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Oluşturulan TIFF görüntüsünün boyutunu belirtir. |
| [getDpiX()](#getDpiX--) | İnç başına nokta cinsinden yatay çözünürlüğü belirtir. |
| [setDpiX(long value)](#setDpiX-long-) | İnç başına nokta cinsinden yatay çözünürlüğü belirtir. |
| [getDpiY()](#getDpiY--) | İnç başına nokta cinsinden dikey çözünürlüğü belirtir. |
| [setDpiY(long value)](#setDpiY-long-) | İnç başına nokta cinsinden dikey çözünürlüğü belirtir. |
| [getCompressionType()](#getCompressionType--) | Sıkıştırma türünü belirtir. |
| [setCompressionType(int value)](#setCompressionType-int-) | Sıkıştırma türünü belirtir. |
| [getPixelFormat()](#getPixelFormat--) | Oluşturulan görüntüler için piksel biçimini belirtir. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Oluşturulan görüntüler için piksel biçimini belirtir. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Renkli bir görüntüyü siyah-beyaz görüntüye dönüştürme algoritmasını belirtir. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Renkli bir görüntüyü siyah-beyaz görüntüye dönüştürme algoritmasını belirtir. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Varsayılan yapıcı.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Yalnızca okuma [IInkOptions](../../com.aspose.slides/iinkoptions)

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

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```


Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dir, bu da oluşturulan görüntü boyutlarının sunum slayt boyutuna göre hesaplanacağı anlamına gelir. Okuma/Yazma [Size](../../com.aspose.slides.android/size).

**Döndürür:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```


Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dir, bu da oluşturulan görüntü boyutlarının sunum slayt boyutuna göre hesaplanacağı anlamına gelir. Okuma/Yazma [Size](../../com.aspose.slides.android/size).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


İnç başına nokta cinsinden yatay çözünürlüğü belirtir. Okuma/Yazma long.

**Döndürür:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


İnç başına nokta cinsinden yatay çözünürlüğü belirtir. Okuma/Yazma long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


İnç başına nokta cinsinden dikey çözünürlüğü belirtir. Okuma/Yazma long.

**Döndürür:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


İnç başına nokta cinsinden dikey çözünürlüğü belirtir. Okuma/Yazma long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Sıkıştırma türünü belirtir. Okuma/Yazma [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Döndürür:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Sıkıştırma türünü belirtir. Okuma/Yazma [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Oluşturulan görüntüler için piksel biçimini belirtir. Okuma/Yazma [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Döndürür:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Oluşturulan görüntüler için piksel biçimini belirtir. Okuma/Yazma [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandoff(HandoutType.Handouts4Horizontal);
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
public final int getBwConversionMode()
```


Renkli bir görüntüyü siyah-beyaz görüntüye dönüştürme algoritmasını belirtir. Bu seçenek yalnızca CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) veya [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) olduğunda uygulanır. Okuma/Yazma [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Varsayılan [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public final void setBwConversionMode(int value)
```


Renkli bir görüntüyü siyah-beyaz görüntüye dönüştürme algoritmasını belirtir. Bu seçenek yalnızca CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) veya [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) olduğunda uygulanır. Okuma/Yazma [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Varsayılan [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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