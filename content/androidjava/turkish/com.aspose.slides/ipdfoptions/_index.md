---
title: IPdfOptions
second_title: Java API Referansı ile Android için Aspose.Slides
description: Bir sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/ipdfoptions/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Bir sunumun Pdf formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Belge içindeki tüm metin içeriği için kullanılacak sıkıştırma türünü belirtir. |
| [setTextCompression(int value)](#setTextCompression-int-) | Belge içindeki tüm metin içeriği için kullanılacak sıkıştırma türünü belirtir. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Her resim için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Her resim için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | ASCII karakterleri 32-127 için True Type yazı tiplerini gömmek için true. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | ASCII karakterleri 32-127 için True Type yazı tiplerini gömmek için true. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides'in ortak olarak kabul edeceği, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini döndürür veya ayarlar. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides'in ortak olarak kabul edeceği, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini döndürür veya ayarlar. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Yazı tipinin tüm karakterlerinin gömülüp gömülmeyeceğini veya yalnızca kullanılan alt kümenin gömülüp gömülmeyeceğini belirler. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Yazı tipinin tüm karakterlerinin gömülüp gömülmeyeceğini veya yalnızca kullanılan alt kümenin gömülüp gömülmeyeceğini belirler. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. |
| [getJpegQuality()](#getJpegQuality--) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. |
| [getCompliance()](#getCompliance--) | Oluşturulan PDF belgesi için istenen uyumluluk düzeyini belirtir. |
| [setCompliance(int value)](#setCompliance-int-) | Oluşturulan PDF belgesi için istenen uyumluluk düzeyini belirtir. |
| [getPassword()](#getPassword--) | PDF belgesini korumak için kullanıcı şifresini ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF belgesini korumak için kullanıcı şifresini ayarlar. |
| [getAccessPermissions()](#getAccessPermissions--) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir bayrak kümesi içerir. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir bayrak kümesi içerir. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. |
| [getSufficientResolution()](#getSufficientResolution--) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Her slaytın etrafına siyah çerçeve çizmek için true. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Her slaytın etrafına siyah çerçeve çizmek için true. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Görüntünün şeffaf rengini alır veya ayarlar. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Görüntünün şeffaf rengini alır veya ayarlar. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Belirtilen şeffaf rengi bir görüntüye uygular, true ise. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Belirtilen şeffaf rengi bir görüntüye uygular, true ise. |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |
| [getIncludeOleData()](#getIncludeOleData--) | Sunumdaki tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için true. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Sunumdaki tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için true. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Belge içindeki tüm metin içeriği için kullanılacak sıkıştırma türünü belirtir. Okuma/Yazma [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Varsayılan [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Döndürür:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Belge içindeki tüm metin içeriği için kullanılacak sıkıştırma türünü belirtir. Okuma/Yazma [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Varsayılan [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Her resim için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. True olarak ayarlanırsa, sunumdaki her resim için en uygun sıkıştırma algoritması seçilir ve bu, sonuç PDF belgesinin daha küçük olmasına yol açar.

--------------------

En iyi görüntü sıkıştırma oranı seçimi işlem açısından maliyetlidir ve ek RAM tüketir; bu seçenek varsayılan olarak false’tur.

--------------------

Varsayılan false.

**Döndürür:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Her resim için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. True olarak ayarlanırsa, sunumdaki her resim için en uygun sıkıştırma algoritması seçilir ve bu, sonuç PDF belgesinin daha küçük olmasına yol açar.

--------------------

En iyi görüntü sıkıştırma oranı seçimi işlem açısından maliyetlidir ve ek RAM tüketir; bu seçenek varsayılan olarak false’tur.

--------------------

Varsayılan false.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

ASCII karakterleri 32-127 için True Type yazı tiplerini gömmek için true. 127’den büyük karakter kodları için yazı tipleri her zaman gömülür. Okuma/Yazma boolean.

--------------------

Varsayılan **true**.

**Döndürür:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

ASCII karakterleri 32-127 için True Type yazı tiplerini gömmek için true. 127’den büyük karakter kodları için yazı tipleri her zaman gömülür. Okuma/Yazma boolean.

--------------------

Varsayılan **true**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan false.

**Döndürür:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan false.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Aspose.Slides'in ortak olarak kabul edeceği, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini döndürür veya ayarlar. Okuma/Yazma String[].

**Döndürür:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides'in ortak olarak kabul edeceği, kullanıcı tanımlı yazı tipi aileleri adlarının bir dizisini döndürür veya ayarlar. Okuma/Yazma String[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Yazı tipinin tüm karakterlerinin gömülüp gömülmeyeceğini veya yalnızca kullanılan alt kümenin gömülüp gömülmeyeceğini belirler. Okuma/Yazma boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Yazı tipinin tüm karakterlerinin gömülüp gömülmeyeceğini veya yalnızca kullanılan alt kümenin gömülüp gömülmeyeceğini belirler. Okuma/Yazma boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yöntem, belirli yazı tiplerinde sonuç PDF'deki metin kalitesini artırabilir. Okuma/Yazma boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yöntem, belirli yazı tiplerinde sonuç PDF'deki metin kalitesini artırabilir. Okuma/Yazma boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okuma/Yazma byte.

--------------------

Yalnızca belge JPEG görüntüleri içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken belgedeki görüntülerin kalitesini ayarlamak için kullanın. Değer 0 ile 100 arasında değişebilir; 0 en düşük kalite ama en yüksek sıkıştırma, 100 ise en yüksek kalite ama en düşük sıkıştırma anlamına gelir.

Varsayılan değer **100**.

**Döndürür:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okuma/Yazma byte.

--------------------

Yalnızca belge JPEG görüntüleri içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken belgedeki görüntülerin kalitesini ayarlamak için kullanın. Değer 0 ile 100 arasında değişebilir; 0 en düşük kalite ama en yüksek sıkıştırma, 100 ise en yüksek kalite ama en düşük sıkıştırma anlamına gelir.

Varsayılan değer **100**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Oluşturulan PDF belgesi için istenen uyumluluk düzeyini belirtir. Okuma/Yazma [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Varsayılan [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Döndürür:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Oluşturulan PDF belgesi için istenen uyumluluk düzeyini belirtir. Okuma/Yazma [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Varsayılan [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

PDF belgesini korumak için kullanıcı şifresini ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

PDF belgesini korumak için kullanıcı şifresini ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir bayrak kümesi içerir. Bkz. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir bayrak kümesi içerir. Bkz. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. Okuma/Yazma boolean.

--------------------

Varsayılan **true**. Pdf belgesi vektör grafikler ve raster görüntüler içerebilir. SaveMetafilesAsPng true olarak ayarlanırsa kaynak Metafile görüntüsü PNG formatına dönüştürülür ve Pdf’e raster görüntü olarak kaydedilir. SaveMetafilesAsPng false ise kaynak Metafile Pdf vektör grafiklerine dönüştürülür. Her iki yaklaşımın da avantajları ve dezavantajları vardır. Örneğin Metafile PNG’ye dönüştürülürse, sonuç belge ölçeklendirilirken kalite kaybı meydana gelebilir. Metafile Pdf vektör grafiklerine dönüştürülürse, Pdf görüntüleme aracında performans sorunları oluşabilir.

**Döndürür:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. Okuma/Yazma boolean.

--------------------

Varsayılan **true**. Pdf belgesi vektör grafikler ve raster görüntüler içerebilir. SaveMetafilesAsPng true olarak ayarlanırsa kaynak Metafile görüntüsü PNG formatına dönüştürülür ve Pdf’e raster görüntü olarak kaydedilir. SaveMetafilesAsPng false ise kaynak Metafile Pdf vektör grafiklerine dönüştürülür. Her iki yaklaşımın da avantajları ve dezavantajları vardır. Örneğin Metafile PNG’ye dönüştürülürse, sonuç belge ölçeklendirilirken kalite kaybı meydana gelebilir. Metafile Pdf vektör grafiklerine dönüştürülürse, Pdf görüntüleme aracında performans sorunları oluşabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. Okuma/Yazma float.

Değer: Bu parametrenin etkisi birkaç faktöre bağlıdır. Algoritma, özellik değeri, kaynak görüntü boyutu ve görüntü çerçevesi boyutuna göre en iyi çıktı görüntü boyutunu almaya çalışır. Benzer özellik değerlerinin kullanılması aynı sonucu verebilir. Görünür etki için 16 ya da 32 adım kullanılması önerilir.

--------------------

Özellik dosya boyutunu, dışa aktarım süresini ve görüntü kalitesini etkiler.

Varsayılan değer **96**.

**Döndürür:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. Okuma/Yazma float.

Değer: Bu parametrenin etkisi birkaç faktöre bağlıdır. Algoritma, özellik değeri, kaynak görüntü boyutu ve görüntü çerçevesi boyutuna göre en iyi çıktı görüntü boyutunu almaya çalışır. Benzer özellik değerlerinin kullanılması aynı sonucu verebilir. Görünür etki için 16 ya da 32 adım kullanılması önerilir.

--------------------

Özellik dosya boyutunu, dışa aktarım süresini ve görüntü kalitesini etkiler.

Varsayılan değer **96**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Her slaytın etrafına siyah çerçeve çizmek için true. Okuma/Yazma boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Her slaytın etrafına siyah çerçeve çizmek için true. Okuma/Yazma boolean.

--------------------

Varsayılan **false**.

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Görüntünün şeffaf rengini alır veya ayarlar.

Değer: Görüntünün şeffaf rengi.

**Döndürür:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Görüntünün şeffaf rengini alır veya ayarlar.

Değer: Görüntünün şeffaf rengi.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Belirtilen şeffaf rengi bir görüntüye uygular, true ise.

**Döndürür:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Belirtilen şeffaf rengi bir görüntüye uygular, true ise.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Yalnızca okuma [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Sunumdaki tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için true. Okuma/Yazma boolean .

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
>      if (pres != null) presentation.dispose();
>  }
> ```

--------------------

Varsayılan **false** .

**Döndürür:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

Sunumdaki tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için true. Okuma/Yazma boolean .

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