---
title: TiffOptions
second_title: Aspose.Slides için Java API Referansı
description: Sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/tiffoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Sunumun TIFF formatında kaydedilmesini kontrol eden seçenekler sağlar.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Sunumu TIFF belgesine kaydediyor
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // TiffOptions sınıfını örnekliyor
>      TiffOptions opts = new TiffOptions();
>      // Sıkıştırma tipini ayarlama
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
>      // Görüntü DPI'sını ayarlama
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Görüntü Boyutunu Ayarla
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Sunumu belirtilen görüntü boyutuyla TIFF olarak kaydet
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat aşağıdaki değerleri içerir (belgeden görülebileceği gibi):
>      //Format1bppIndexed; // Piksel başına 1 bit, indeksli.
>      //Format4bppIndexed; // Piksel başına 4 bit, indeksli.
>      //Format8bppIndexed; // Piksel başına 8 bit, indeksli.
>      //Format24bppRgb; // Piksel başına 24 bit, RGB.
>      //Format32bppArgb; // Piksel başına 32 bit, ARGB.
> 
>      // Sunumu belirtilen görüntü boyutuyla TIFF olarak kaydet
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yapıcılar

| Constructor | Description |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Varsayılan yapıcı. |
## Yöntemler

| Method | Description |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getImageSize()](#getImageSize--) | Oluşturulan TIFF görüntüsünün boyutunu belirtir. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Oluşturulan TIFF görüntüsünün boyutunu belirtir. |
| [getDpiX()](#getDpiX--) | İnç başına nokta (dpi) cinsinden yatay çözünürlüğü belirtir. |
| [setDpiX(long value)](#setDpiX-long-) | İnç başına nokta (dpi) cinsinden yatay çözünürlüğü belirtir. |
| [getDpiY()](#getDpiY--) | İnç başına nokta (dpi) cinsinden dikey çözünürlüğü belirtir. |
| [setDpiY(long value)](#setDpiY-long-) | İnç başına nokta (dpi) cinsinden dikey çözünürlüğü belirtir. |
| [getCompressionType()](#getCompressionType--) | Sıkıştırma türünü belirtir. |
| [setCompressionType(int value)](#setCompressionType-int-) | Sıkıştırma türünü belirtir. |
| [getPixelFormat()](#getPixelFormat--) | Oluşturulan görüntüler için piksel biçimini belirtir. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Oluşturulan görüntüler için piksel biçimini belirtir. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Renkli bir görüntüyü siyah beyaza dönüştürmek için kullanılan algoritmayı belirtir. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Renkli bir görüntüyü siyah beyaza dönüştürmek için kullanılan algoritmayı belirtir. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Varsayılan yapıcı.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Salt okunur [IInkOptions](../../com.aspose.slides/iinkoptions)

**Dönüş Değeri:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değer false'tur.

**Dönüş Değeri:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değer false'tur.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```

Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dır; bu, oluşturulan görüntü boyutlarının sunum slayt boyutuna göre hesaplanacağı anlamına gelir. Okunur/Yazılabilir java.awt.Dimension.

**Dönüş Değeri:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```

Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dır; bu, oluşturulan görüntü boyutlarının sunum slayt boyutuna göre hesaplanacağı anlamına gelir. Okunur/Yazılabilir java.awt.Dimension.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

İnç başına nokta (dpi) cinsinden yatay çözünürlüğü belirtir. Okunur/Yazılabilir long.

**Dönüş Değeri:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

İnç başına nokta (dpi) cinsinden yatay çözünürlüğü belirtir. Okunur/Yazılabilir long.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

İnç başına nokta (dpi) cinsinden dikey çözünürlüğü belirtir. Okunur/Yazılabilir long.

**Dönüş Değeri:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

İnç başına nokta (dpi) cinsinden dikey çözünürlüğü belirtir. Okunur/Yazılabilir long.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Sıkıştırma türünü belirtir. Okunur/Yazılabilir [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Dönüş Değeri:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Sıkıştırma türünü belirtir. Okunur/Yazılabilir [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Oluşturulan görüntüler için piksel biçimini belirtir. Okunur/Yazılabilir [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Dönüş Değeri:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Oluşturulan görüntüler için piksel biçimini belirtir. Okunur/Yazılabilir [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
**Dönüş Değeri:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Sunum dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

Renkli bir görüntüyü siyah beyaza dönüştürmek için kullanılan algoritmayı belirtir. Bu seçenek yalnızca CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) veya [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) olarak ayarlandığında uygulanır. Okunur/Yazılabilir [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Varsayılan [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
**Dönüş Değeri:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

Renkli bir görüntüyü siyah beyaza dönüştürmek için kullanılan algoritmayı belirtir. Bu seçenek yalnızca CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) veya [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) olarak ayarlandığında uygulanır. Okunur/Yazılabilir [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Varsayılan [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |