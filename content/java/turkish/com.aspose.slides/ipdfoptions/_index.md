---
title: IPdfOptions
second_title: Aspose.Slides for Java API Referansı
description: Sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
url: /tr/com.aspose.slides/ipdfoptions/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Belge içindeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir. |
| [setTextCompression(int value)](#setTextCompression-int-) | Belge içindeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Her görüntü için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Her görüntü için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | ASCII karakterleri 32-127 için true ayarlayarak True Type yazı tiplerini göm. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | ASCII karakterleri 32-127 için true ayarlayarak True Type yazı tiplerini göm. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarını içeren bir dizi döndürür veya ayarlar. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarını içeren bir dizi döndürür veya ayarlar. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. |
| [getJpegQuality()](#getJpegQuality--) | PDF belgesindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | PDF belgesindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. |
| [getCompliance()](#getCompliance--) | Oluşturulan PDF belgesi için istenen uyumluluk düzeyini belirtir. |
| [setCompliance(int value)](#setCompliance-int-) | Oluşturulan PDF belgesi için istenen uyumluluk düzeyini belirtir. |
| [getPassword()](#getPassword--) | PDF belgesini korumak için kullanıcı şifresini ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | PDF belgesini korumak için kullanıcı şifresini ayarlar. |
| [getAccessPermissions()](#getAccessPermissions--) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrağı içerir. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrağı içerir. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. |
| [getSufficientResolution()](#getSufficientResolution--) | PDF belgesindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | PDF belgesindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Her slaytın etrafına siyah çerçeve çizmek için true. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Her slaytın etrafına siyah çerçeve çizmek için true. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada yerleştirileceği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada yerleştirileceği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Görüntünün saydam rengini alır veya ayarlar. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Görüntünün saydam rengini alır veya ayarlar. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Belirtilen saydam rengi bir görüntüye uygular, eğer true ise. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Belirtilen saydam rengi bir görüntüye uygular, eğer true ise. |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |
| [getIncludeOleData()](#getIncludeOleData--) | Sunumdan tüm OLE verilerini sonuç PDF'de yerleşik dosyalara dönüştürmek için true. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Sunumdan tüm OLE verilerini sonuç PDF'de yerleşik dosyalara dönüştürmek için true. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Belge içindeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir. Okunabilir/Yazılabilir [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

Varsayılan [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Döndürür:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Belge içindeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir. Okunabilir/Yazılabilir [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

Varsayılan [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Her görüntü için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. True olarak ayarlandığında, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir, bu da oluşan PDF belgesinin boyutunun daha küçük olmasını sağlar.

En iyi görüntü sıkıştırma oranı seçimi hesaplama açısından maliyetlidir ve ek RAM tüketir, bu seçenek varsayılan olarak false'tur.

Varsayılan false.

**Döndürür:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Her görüntü için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir. True olarak ayarlandığında, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir, bu da oluşan PDF belgesinin boyutunun daha küçük olmasını sağlar.

En iyi görüntü sıkıştırma oranı seçimi hesaplama açısından maliyetlidir ve ek RAM tüketir, bu seçenek varsayılan olarak false'tur.

Varsayılan false.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

ASCII karakterleri 32-127 için true ayarlayarak True Type yazı tiplerini gömer. 127'den büyük karakter kodları için yazı tipleri her zaman gömülür. Okunabilir/Yazılabilir boolean.

Varsayılan **true**.

**Döndürür:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

ASCII karakterleri 32-127 için true ayarlayarak True Type yazı tiplerini gömer. 127'den büyük karakter kodları için yazı tipleri her zaman gömülür. Okunabilir/Yazılabilir boolean.

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

Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarını içeren bir dizi döndürür veya ayarlar. Okunabilir/Yazılabilir String[].

**Döndürür:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Aspose.Slides'in ortak olarak kabul etmesi gereken, kullanıcı tanımlı yazı tipi aileleri adlarını içeren bir dizi döndürür veya ayarlar. Okunabilir/Yazılabilir String[].

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Okunabilir/Yazılabilir boolean.

Varsayılan **false**.

**Döndürür:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Okunabilir/Yazılabilir boolean.

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için sonuç PDF'deki metin kalitesini artırabilir. Okunabilir/Yazılabilir boolean.

Varsayılan **false**.

**Döndürür:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için sonuç PDF'deki metin kalitesini artırabilir. Okunabilir/Yazılabilir boolean.

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

PDF belgesindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okunabilir/Yazılabilir byte.

Yalnızca belge JPEG görüntüleri içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken belgedeki görüntülerin kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kalite ama maksimum sıkıştırma, 100 ise en yüksek kalite ama minimum sıkıştırma anlamına gelir.

Varsayılan değer **100**.

**Döndürür:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

PDF belgesindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar. Okunabilir/Yazılabilir byte.

Yalnızca belge JPEG görüntüleri içerdiğinde etkili olur.

Bu özelliği, PDF formatında kaydederken belgedeki görüntülerin kalitesini almak veya ayarlamak için kullanın. Değer 0 ile 100 arasında değişir; 0 en düşük kalite ama maksimum sıkıştırma, 100 ise en yüksek kalite ama minimum sıkıştırma anlamına gelir.

Varsayılan değer **100**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Oluşturulan PDF belgesi için istenen uyumluluk düzeyi. Okunabilir/Yazılabilir [PdfCompliance](../../com.aspose.slides/pdfcompliance).

Varsayılan [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Döndürür:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Oluşturulan PDF belgesi için istenen uyumluluk düzeyi. Okunabilir/Yazılabilir [PdfCompliance](../../com.aspose.slides/pdfcompliance).

Varsayılan [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

PDF belgesini korumak için kullanıcı şifresini ayarlama. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

PDF belgesini korumak için kullanıcı şifresini ayarlama. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrağı içerir. Bakınız [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrağı içerir. Bakınız [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. Okunabilir/Yazılabilir boolean.

Varsayılan **true**. PDF belgesi vektör grafikleri ve raster görüntüler içerebilir. SaveMetafilesAsPng true olarak ayarlandığında, kaynak Metafile görüntüsü PNG formatına dönüştürülür ve PDF'ye raster görüntü olarak kaydedilir. SaveMetafilesAsPng false olarak ayarlandığında, kaynak Metafile PDF vektör grafiğine dönüştürülür. Her yaklaşımın avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürüldüğünde, ortaya çıkan belgenin ölçeklendirilmesi sırasında bazı kalite kayıpları olabilir. Metafile PDF vektör grafiğine dönüştürüldüğünde, PDF görüntüleyicide performans sorunları ortaya çıkabilir.

**Döndürür:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için true. Okunabilir/Yazılabilir boolean.

Varsayılan **true**. PDF belgesi vektör grafikleri ve raster görüntüler içerebilir. SaveMetafilesAsPng true olarak ayarlandığında, kaynak Metafile görüntüsü PNG formatına dönüştürülür ve PDF'ye raster görüntü olarak kaydedilir. SaveMetafilesAsPng false olarak ayarlandığında, kaynak Metafile PDF vektör grafiğine dönüştürülür. Her yaklaşımın avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürüldüğünde, ortaya çıkan belgenin ölçeklendirilmesi sırasında bazı kalite kayıpları olabilir. Metafile PDF vektör grafiğine dönüştürüldüğünde, PDF görüntüleyicide performans sorunları ortaya çıkabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

PDF belgesindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. Okunabilir/Yazılabilir float.

Değer: Bu parametrenin etkisi birkaç faktöre bağlıdır. Algoritma, özellik değerine, kaynak görüntü boyutuna ve görüntü çerçeve boyutuna göre en iyi çıkış görüntü boyutunu elde etmeye çalışır. Benzer özellik değerlerinin kullanılması aynı sonucu verebilir. Görünür etki elde etmek için 16 veya 32 adım kullanılması önerilir.

Özellik dosya boyutunu, dışa aktarma süresini ve görüntü kalitesini etkiler.

Varsayılan değer **96**.

**Döndürür:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

PDF belgesindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar. Okunabilir/Yazılabilir float.

Değer: Bu parametrenin etkisi birkaç faktöre bağlıdır. Algoritma, özellik değerine, kaynak görüntü boyutuna ve görüntü çerçeve boyutuna göre en iyi çıkış görüntü boyutunu elde etmeye çalışır. Benzer özellik değerlerinin kullanılması aynı sonucu verebilir. Görünür etki elde etmek için 16 veya 32 adım kullanılması önerilir.

Özellik dosya boyutunu, dışa aktarma süresini ve görüntü kalitesini etkiler.

Varsayılan değer **96**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Her slaytın etrafına siyah çerçeve çizmek için true. Okunabilir/Yazılabilir boolean.

Varsayılan **false**.

**Döndürür:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Her slaytın etrafına siyah çerçeve çizmek için true. Okunabilir/Yazılabilir boolean.

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunumu dışa aktarırken slaytların sayfada yerleştirileceği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Sunumu dışa aktarırken slaytların sayfada yerleştirileceği modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract Color getImageTransparentColor()
```

Görüntünün saydam rengini alır veya ayarlar.

Değer: Görüntünün saydam rengi.

**Döndürür:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Görüntünün saydam rengini alır veya ayarlar.

Değer: Görüntünün saydam rengi.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Belirtilen saydam rengi bir görüntüye uygular, eğer true ise.

**Döndürür:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Belirtilen saydam rengi bir görüntüye uygular, eğer true ise.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Salt-okunur [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Sunumdan tüm OLE verilerini sonuç PDF'de yerleşik dosyalara dönüştürmek için true. Okunabilir/Yazılabilir boolean.

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

Varsayılan **false**.

**Döndürür:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

Sunumdan tüm OLE verilerini sonuç PDF'de yerleşik dosyalara dönüştürmek için true. Okunabilir/Yazılabilir boolean.

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

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |