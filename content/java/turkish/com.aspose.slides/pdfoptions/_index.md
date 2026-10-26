---
title: PdfOptions
second_title: Aspose.Slides için Java API Referansı
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

Sunumun PDF formatında kaydedilmesini kontrol eden seçenekler sağlar.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // PdfOptions sınıfını örnekler
>      PdfOptions pdfOptions = new PdfOptions();
>      // Jpeg kalitesini ayarlar
>      pdfOptions.setJpegQuality((byte)90);
>      // Metafile davranışını ayarlar
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Metin sıkıştırma seviyesini ayarlar
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // PDF standardını tanımlar
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Sunumu PDF olarak kaydeder
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
>      // Sunumu PDF olarak kaydeder
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
>      // PDF şifresi ve erişim izinlerini ayarlar
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Sunumu PDF olarak kaydeder
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
>          // Slayt tipi ve boyutunu ayarlar
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
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getTextCompression()](#getTextCompression--) | Belgedeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir. |
| [setTextCompression(int value)](#setTextCompression-int-) | Belgedeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Her resim için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Her resim için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Aspose.Slides'in ASCII (33..127 kod aralığı) metni için ortak yazı tiplerini gömeceğini belirler. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Aspose.Slides'in ASCII (33..127 kod aralığı) metni için ortak yazı tiplerini gömeceğini belirler. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides'in ortak olarak kabul edeceği yazı tipi ailelerinin kullanıcı tarafından tanımlanan adlarını içeren bir dizi döndürür veya ayarlar. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides'in ortak olarak kabul edeceği yazı tipi ailelerinin kullanıcı tarafından tanımlanan adlarını içeren bir dizi döndürür veya ayarlar. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Yazı tipinin tüm karakterlerinin gömülüp gömülmeyeceğini ya da yalnızca kullanılan alt kümenin gömülüp gömülmeyeceğini belirler. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Yazı tipinin tüm karakterlerinin gömülüp gömülmeyeceğini ya da yalnızca kullanılan alt kümenin gömülüp gömülmeyeceğini belirler. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Yazı tipi kalın biçimlendirmeyi desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Yazı tipi kalın biçimlendirmeyi desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. |
| [getJpegQuality()](#getJpegQuality--) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. |
| [getCompliance()](#getCompliance--) | Oluşturulan PDF belgesi için istenen uyumluluk seviyesini belirler. |
| [setCompliance(int value)](#setCompliance-int-) | Oluşturulan PDF belgesi için istenen uyumluluk seviyesini belirler. |
| [getPassword()](#getPassword--) | PDF belgesini korumak için kullanıcı şifresi ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF belgesini korumak için kullanıcı şifresi ayarlar. |
| [getAccessPermissions()](#getAccessPermissions--) | Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayrak setini içerir. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayrak setini içerir. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için **true**. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için **true**. |
| [getSufficientResolution()](#getSufficientResolution--) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Her slaytın etrafına siyah çerçeve çizmek için **true**. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Her slaytın etrafına siyah çerçeve çizmek için **true**. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Görüntünün saydam renk değerini alır veya ayarlar. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Görüntünün saydam renk değerini alır veya ayarlar. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | **true** ise belirtilen saydam rengi görüntüye uygular. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | **true** ise belirtilen saydam rengi görüntüye uygular. |
| [getIncludeOleData()](#getIncludeOleData--) | Sunumdan tüm OLE verilerinin sonuç PDF içinde gömülü dosyalara dönüştürülmesi için **true**. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Sunumdan tüm OLE verilerinin sonuç PDF içinde gömülü dosyalara dönüştürülmesi için **true**. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Varsayılan yapıcı.

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

**Dönüş:**
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Salt okunur [IInkOptions](../../com.aspose.slides/iinkoptions)

**Dönüş:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**.

**Dönüş:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Belgedeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir. Okunabilir/Yazılabilir [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Varsayılan **[PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)**.

**Dönüş:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Belgedeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir. Okunabilir/Yazılabilir [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Varsayılan **[PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate)**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Her resim için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. **true** olarak ayarlandığında, sunumdaki her resim için en uygun sıkıştırma algoritması seçilir ve bu, oluşan PDF belgesinin daha küçük olmasını sağlar.

--------------------

En iyi görüntü sıkıştırma oranı seçimi işlemci açısından maliyetlidir ve ek RAM tüketir; bu seçenek varsayılan olarak **false**.

--------------------

Varsayılan **false**.

**Dönüş:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Her resim için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. **true** olarak ayarlandığında, sunumdaki her resim için en uygun sıkıştırma algoritması seçilir ve bu, oluşan PDF belgesinin daha küçük olmasını sağlar.

--------------------

En iyi görüntü sıkıştırma oranı seçimi işlemci açısından maliyetlidir ve ek RAM tüketir; bu seçenek varsayılan olarak **false**.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Aspose.Slides'in ASCII (33..127 kod aralığı) metni için ortak yazı tiplerini gömeceğini belirler. 127'den büyük kodlar için yazı tipleri her zaman gömülür. Ortak yazı tipleri listesi PDF'in temel 14 yazı tipini ve ek kullanıcı belirttiği yazı tiplerini içerir. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **true**.

**Dönüş:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Aspose.Slides'in ASCII (33..127 kod aralığı) metni için ortak yazı tiplerini gömeceğini belirler. 127'den büyük kodlar için yazı tipleri her zaman gömülür. Ortak yazı tipleri listesi PDF'in temel 14 yazı tipini ve ek kullanıcı belirttiği yazı tiplerini içerir. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **true**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides'in ortak olarak kabul etmesi gereken yazı tipi ailelerinin kullanıcı tarafından tanımlanan adlarını içeren bir dizi döndürür veya ayarlar. Okunabilir/Yazılabilir String[].

**Dönüş:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides'in ortak olarak kabul etmesi gereken yazı tipi ailelerinin kullanıcı tarafından tanımlanan adlarını içeren bir dizi döndürür veya ayarlar. Okunabilir/Yazılabilir String[].

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Yazı tipinin tüm karakterlerinin gömülüp gömülmeyeceğini ya da yalnızca kullanılan alt kümenin gömülüp gömülmeyeceğini belirler. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Dönüş:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Yazı tipinin tüm karakterlerinin gömülüp gömülmeyeceğini ya da yalnızca kullanılan alt kümenin gömülüp gömülmeyeceğini belirler. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Yazı tipi kalın biçimlendirmeyi desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için PDF'deki metin kalitesini artırabilir. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Dönüş:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Yazı tipi kalın biçimlendirmeyi desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için PDF'deki metin kalitesini artırabilir. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okunabilir/Yazılabilir byte.

--------------------

Yalnızca belge JPEG görüntüler içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken belge içindeki görüntü kalitesini ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kalite ama maksimum sıkıştırma, 100 en yüksek kalite ama minimum sıkıştırma anlamına gelir.

Varsayılan değer **100**.

**Dönüş:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okunabilir/Yazılabilir byte.

--------------------

Yalnızca belge JPEG görüntüler içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken belge içindeki görüntü kalitesini ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kalite ama maksimum sıkıştırma, 100 en yüksek kalite ama minimum sıkıştırma anlamına gelir.

Varsayılan değer **100**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Oluşturulan PDF belgesi için istenen uyumluluk seviyesini belirler. Okunabilir/Yazılabilir [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Varsayılan **[PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)**.

**Dönüş:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Oluşturulan PDF belgesi için istenen uyumluluk seviyesini belirler. Okunabilir/Yazılabilir [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Varsayılan **[PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17)**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

PDF belgesini korumak için kullanıcı şifresi ayarlar. Okunabilir/Yazılabilir String.

**Dönüş:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

PDF belgesini korumak için kullanıcı şifresi ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayrak setini içerir. Bakınız [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Dönüş:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bayrak setini içerir. Bakınız [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için **true**. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **true**. PDF belgesi vektör grafikler ve raster görüntüler içerebilir. SaveMetafilesAsPng **true** olarak ayarlandığında kaynak Metafile görüntüsü PNG formatına dönüştürülür ve PDF içinde raster görüntü olarak kaydedilir. **false** olduğunda kaynak Metafile PDF vektör grafiği olarak kaydedilir. Her iki yaklaşımın da avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürüldüğünde sonuç belge ölçeklendirilirken kalite kaybı olasıdır. Vektör grafiklere dönüştürüldüğünde PDF görüntüleyicide performans sorunları ortaya çıkabilir.

**Dönüş:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için **true**. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **true**. PDF belgesi vektör grafikler ve raster görüntüler içerebilir. SaveMetafilesAsPng **true** olarak ayarlandığında kaynak Metafile görüntüsü PNG formatına dönüştürülür ve PDF içinde raster görüntü olarak kaydedilir. **false** olduğunda kaynak Metafile PDF vektör grafiği olarak kaydedilir. Her iki yaklaşımın da avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürüldüğünde sonuç belge ölçeklendirilirken kalite kaybı olasıdır. Vektör grafiklere dönüştürüldüğünde PDF görüntüleyicide performans sorunları ortaya çıkabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. Okunabilir/Yazılabilir float.

Değer: Bu parametrenin etkisi birkaç faktöre bağlıdır. Algoritma, özellik değeri, kaynak görüntü boyutu ve görüntü çerçevesi boyutuna göre en iyi çıktı görüntü boyutunu almaya çalışır. Benzer özellik değerlerinin kullanılması aynı sonucu verebilir. Görünür etki elde etmek için 16 veya 32 adım kullanılması önerilir.

--------------------

Özellik dosya boyutu, dışa aktarma süresi ve görüntü kalitesi üzerinde etkili olur.

Varsayılan değer **96**.

**Dönüş:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. Okunabilir/Yazılabilir float.

Değer: Bu parametrenin etkisi birkaç faktöre bağlıdır. Algoritma, özellik değeri, kaynak görüntü boyutu ve görüntü çerçevesi boyutuna göre en iyi çıktı görüntü boyutunu almaya çalışır. Benzer özellik değerlerinin kullanılması aynı sonucu verebilir. Görünür etki elde etmek için 16 veya 32 adım kullanılması önerilir.

--------------------

Özellik dosya boyutu, dışa aktarma süresi ve görüntü kalitesi üzerinde etkili olur.

Varsayılan değer **96**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Her slaytın etrafına siyah çerçeve çizmek için **true**. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Dönüş:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Her slaytın etrafına siyah çerçeve çizmek için **true**. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Görüntünün saydam renk değerini alır veya ayarlar.

Değer: Görüntünün saydam rengi.

**Dönüş:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Görüntünün saydam renk değerini alır veya ayarlar.

Değer: Görüntünün saydam rengi.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Belirtilen saydam rengi bir görüntüye **true** ise uygular.

**Dönüş:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Belirtilen saydam rengi bir görüntüye **true** ise uygular.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Sunumdan tüm OLE verilerinin sonuç PDF içinde gömülü dosyalara dönüştürülmesi için **true**. Okunabilir/Yazılabilir boolean.

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

Varsayılan **false**.

**Dönüş:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Sunumdan tüm OLE verilerinin sonuç PDF içinde gömülü dosyalara dönüştürülmesi için **true**. Okunabilir/Yazılabilir boolean.

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

Varsayılan **false**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |