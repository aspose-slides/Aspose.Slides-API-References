---
title: PdfOptions
second_title: Java API Referansı aracılığıyla Aspose.Slides for Android
description: Bir sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/pdfoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Bir sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions sınıfını örnekler
>      PdfOptions pdfOptions = new PdfOptions();
>      // JPEG kalitesini ayarlar
>      pdfOptions.setJpegQuality((byte)90);
>      // Metafile davranışını ayarlar
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Metin sıkıştırma seviyesini ayarlar
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // PDF standardını tanımlar
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Saves the presentation as a PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // PowerPoint dosyasını temsil eden Presentation sınıfını örnekler
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions sınıfını örnekler
>      PdfOptions pdfOptions = new PdfOptions();
>      // Gizli slaytları ekler
>      pdfOptions.setShowHiddenSlides(true);
>      // Saves the presentation as a PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // PowerPoint dosyasını temsil eden Presentation nesnesini örnekler
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions sınıfını örnekler
>      PdfOptions pdfOptions = new PdfOptions();
>      // PDF şifresini ve erişim izinlerini ayarlar
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Saves the presentation as a PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Sunum dosyasını temsil eden Presentation nesnesini örnekler
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Slayt tipini ve boyutunu ayarlar
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Varsayılan yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar. |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getTextCompression()](#getTextCompression--) | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma tipini belirtir. |
| [setTextCompression(int value)](#setTextCompression-int-) | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma tipini belirtir. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Her görüntü için varsayılan yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmemesi gerektiğini gösterir. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Her görüntü için varsayılan yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmemesi gerektiğini gösterir. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Aspose.Slides'in ASCII (33..127 kod aralığı) metin için ortak yazı tiplerini gömmesini belirler. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Aspose.Slides'in ASCII (33..127 kod aralığı) metin için ortak yazı tiplerini gömmesini belirler. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini alır veya ayarlar. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini alır veya ayarlar. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. |
| [getJpegQuality()](#getJpegQuality--) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri alır veya ayarlar. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri alır veya ayarlar. |
| [getCompliance()](#getCompliance--) | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. |
| [setCompliance(int value)](#setCompliance-int-) | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. |
| [getPassword()](#getPassword--) | PDF belgesini korumak için kullanıcı şifresini ayarlama. |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF belgesini korumak için kullanıcı şifresini ayarlama. |
| [getAccessPermissions()](#getAccessPermissions--) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayrak setini içerir. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayrak setini içerir. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için true. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için true. |
| [getSufficientResolution()](#getSufficientResolution--) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri alır veya ayarlar. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri alır veya ayarlar. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Her slaytın etrafına siyah çerçeve çizmek için true. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Her slaytın etrafına siyah çerçeve çizmek için true. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Görüntünün şeffaf renk değerini alır veya ayarlar. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Görüntünün şeffaf renk değerini alır veya ayarlar. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | True ise belirtilen şeffaf rengi bir görüntüye uygular. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | True ise belirtilen şeffaf rengi bir görüntüye uygular. |
| [getIncludeOleData()](#getIncludeOleData--) | Sunumdan tüm OLE verilerinin elde edilen PDF içinde gömülü dosyalara dönüştürülmesi için true. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Sunumdan tüm OLE verilerinin elde edilen PDF içinde gömülü dosyalara dönüştürülmesi için true. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Varsayılan yapıcı.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunumu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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

Sunumu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Yalnızca okuma [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan false'tur.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Belgedeki tüm metin içeriği için kullanılacak sıkıştırma tipini belirtir. Okuma/yazma [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Varsayılan [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Döndürür:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Belgedeki tüm metin içeriği için kullanılacak sıkıştırma tipini belirtir. Okuma/yazma [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Varsayılan [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Her görüntü için varsayılan yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmemesi gerektiğini gösterir. True olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasını sağlar.

--------------------

En iyi görüntü sıkıştırma oranının seçimi hesaplamalı olarak pahalıdır ve ek RAM tüketir; bu seçenek varsayılan olarak false'tur.

--------------------

Varsayılan false'tur.

**Döndürür:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Her görüntü için varsayılan yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmemesi gerektiğini gösterir. True olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasını sağlar.

--------------------

En iyi görüntü sıkıştırma oranının seçimi hesaplamalı olarak pahalıdır ve ek RAM tüketir; bu seçenek varsayılan olarak false'tur.

--------------------

Varsayılan false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Aspose.Slides'in ASCII (33..127 kod aralığı) metin için ortak yazı tiplerini gömmesini belirler. 127'den büyük kodlar için yazı tipleri her zaman gömülür. Ortak yazı tipleri listesi PDF'in temel 14 yazı tipini ve ek kullanıcı belirttiği yazı tiplerini içerir. Okuma/yazma boolean.

--------------------

Varsayılan **true**.

**Döndürür:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Aspose.Slides'in ASCII (33..127 kod aralığı) metin için ortak yazı tiplerini gömmesini belirler. 127'den büyük kodlar için yazı tipleri her zaman gömülür. Ortak yazı tipleri listesi PDF'in temel 14 yazı tipini ve ek kullanıcı belirttiği yazı tiplerini içerir. Okuma/yazma boolean.

--------------------

Varsayılan **true**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini alır veya ayarlar. Okuma/yazma String[].

**Döndürür:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini alır veya ayarlar. Okuma/yazma String[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Okuma/yazma boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Okuma/yazma boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için sonuç PDF'deki metnin kalitesini artırabilir. Okuma/yazma boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için sonuç PDF'deki metnin kalitesini artırabilir. Okuma/yazma boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri alır veya ayarlar. Okuma/yazma byte.

--------------------

Yalnızca belge JPEG görüntüleri içerdiğinde etkili olur.

Bu özelliği PDF formatında kaydederken belgedeki görüntü kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kalite ama en yüksek sıkıştırma, 100 ise en yüksek kalite ama en düşük sıkıştırma anlamına gelir.

Varsayılan değer **100**.

**Döndürür:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri alır veya ayarlar. Okuma/yazma byte.

--------------------

Yalnızca belge JPEG görüntüleri içerdiğinde etkili olur.

Bu özelliği PDF formatında kaydederken belgedeki görüntü kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kalite ama en yüksek sıkıştırma, 100 ise en yüksek kalite ama en düşük sıkıştırma anlamına gelir.

Varsayılan değer **100**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. Okuma/yazma [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Varsayılan [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Döndürür:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. Okuma/yazma [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Varsayılan [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

PDF belgesini korumak için kullanıcı şifresini ayarlama. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

PDF belgesini korumak için kullanıcı şifresini ayarlama. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayrak setini içerir. Bakınız [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayrak setini içerir. Bakınız [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için true. Okuma/yazma boolean.

--------------------

Varsayılan **true**. Pdf belgesi vektör grafikler ve raster görüntüler içerebilir. SaveMetafilesAsPng true ayarlanırsa kaynak Metafile görüntüsü PNG formatına dönüştürülür ve Pdf'e raster görüntü olarak kaydedilir. SaveMetafilesAsPng false ayarlanırsa kaynak Metafile Pdf vektör grafiğine dönüştürülür. Her iki yaklaşımın avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürüldüğünde sonuç belge ölçeklendirilirken bazı kalite kayıpları oluşabilir. Metafile Pdf vektör grafiğine dönüştürüldüğünde Pdf görüntüleme aracında performans sorunları ortaya çıkabilir.

**Döndürür:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için true. Okuma/yazma boolean.

--------------------

Varsayılan **true**. Pdf belgesi vektör grafikler ve raster görüntüler içerebilir. SaveMetafilesAsPng true ayarlanırsa kaynak Metafile görüntüsü PNG formatına dönüştürülür ve Pdf'e raster görüntü olarak kaydedilir. SaveMetafilesAsPng false ayarlanırsa kaynak Metafile Pdf vektör grafiğine dönüştürülür. Her iki yaklaşımın avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürüldüğünde sonuç belge ölçeklendirilirken bazı kalite kayıpları oluşabilir. Metafile Pdf vektör grafiğine dönüştürüldüğünde Pdf görüntüleme aracında performans sorunları ortaya çıkabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri alır veya ayarlar. Okuma/yazma float.

Değer: Bu parametrenin etkisi birkaç faktöre bağlıdır. Algoritma, özellik değerine, kaynak görüntü boyutuna ve görüntü çerçeve boyutuna göre en iyi çıktı görüntü boyutunu elde etmeye çalışır. Benzer özellik değerlerinin kullanılması aynı sonucu verebilir. Görünür etki elde etmek için 16 veya 32 adım kullanılması önerilir.

--------------------

Özellik dosya boyutu, dışa aktarma süresi ve görüntü kalitesi üzerinde etkili olur.

Varsayılan değer **96**.

**Döndürür:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri alır veya ayarlar. Okuma/yazma float.

Değer: Bu parametrenin etkisi birkaç faktöre bağlıdır. Algoritma, özellik değerine, kaynak görüntü boyutuna ve görüntü çerçeve boyutuna göre en iyi çıktı görüntü boyutunu elde etmeye çalışır. Benzer özellik değerlerinin kullanılması aynı sonucu verebilir. Görünür etki elde etmek için 16 veya 32 adım kullanılması önerilir.

--------------------

Özellik dosya boyutu, dışa aktarma süresi ve görüntü kalitesi üzerinde etkili olur.

Varsayılan değer **96**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Her slaytın etrafına siyah çerçeve çizmek için true. Okuma/yazma boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Her slaytın etrafına siyah çerçeve çizmek için true. Okuma/yazma boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Görüntünün şeffaf renk değerini alır veya ayarlar.

Değer: Görüntünün şeffaf rengi.

**Döndürür:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Görüntünün şeffaf renk değerini alır veya ayarlar.

Değer: Görüntünün şeffaf rengi.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

True ise belirtilen şeffaf rengi bir görüntüye uygular.

**Döndürür:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

True ise belirtilen şeffaf rengi bir görüntüye uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Sunumdan tüm OLE verilerinin elde edilen PDF içinde gömülü dosyalara dönüştürülmesi için true. Okuma/yazma  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan **false** .

**Döndürür:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Sunumdan tüm OLE verilerinin elde edilen PDF içinde gömülü dosyalara dönüştürülmesi için true. Okuma/yazma  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan **false** .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |