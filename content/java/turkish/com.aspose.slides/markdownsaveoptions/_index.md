---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Java API Referansı
description: Sunumun markdown olarak kaydedilmesini kontrol eden seçenekleri temsil eder.
type: docs
url: /tr/com.aspose.slides/markdownsaveoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Sunumun markdown olarak kaydedilmesini kontrol eden seçenekleri temsil eder.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getExportType()](#getExportType--) | Sunumu dönüştürmek için markdown belirtimini belirler. |
| [setExportType(int value)](#setExportType-int-) | Sunumu dönüştürmek için markdown belirtimini belirler. |
| [getBasePath()](#getBasePath--) | Kaynaklarla belgeyin kaydedileceği temel yolu belirler. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Kaynaklarla belgeyin kaydedileceği temel yolu belirler. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Görüntüleri kaydetmek için klasör adını belirler. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Görüntüleri kaydetmek için klasör adını belirler. |
| [getNewLineType()](#getNewLineType--) | Oluşturulan belgenin \\r (Macintosh), \\n (Unix) veya \\r\\n (Windows) satır sonlarını kullanıp kullanmayacağını belirtir. |
| [setNewLineType(int value)](#setNewLineType-int-) | Oluşturulan belgenin \\r (Macintosh), \\n (Unix) veya \\r\\n (Windows) satır sonlarını kullanıp kullanmayacağını belirtir. |
| [getShowComments()](#getShowComments--) | Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. |
| [getFlavor()](#getFlavor--) | Sunumu dönüştürmek için markdown belirtimini belirler. |
| [setFlavor(int value)](#setFlavor-int-) | Sunumu dönüştürmek için markdown belirtimini belirler. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır veya ayarlar. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır veya ayarlar. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Markdown dışa aktarımı sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirler. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Markdown dışa aktarımı sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirler. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Doğru olarak ayarlanırsa, boş ya da sadece boşluk içeren satırları son Markdown çıktısından kaldırır. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Doğru olarak ayarlanırsa, boş ya da sadece boşluk içeren satırları son Markdown çıktısından kaldırır. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Markdown dışa aktarımı sırasında SVG olmayan her görüntü (bitmap veya metafile) için gerçekleşir. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Markdown dışa aktarımı sırasında her SVG görüntü için gerçekleşir. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Sunumu dönüştürmek için markdown belirtimini belirler. Varsayılan değer TextOnly'dir.

**Döndürür:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Sunumu dönüştürmek için markdown belirtimini belirler. Varsayılan değer TextOnly'dir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Kaynaklarla belgeyin kaydedileceği temel yolu belirler. Varsayılan değer uygulamanın geçerli dizinidir.

**Döndürür:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Kaynaklarla belgeyin kaydedileceği temel yolu belirler. Varsayılan değer uygulamanın geçerli dizinidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Görüntüleri kaydetmek için klasör adını belirler. Varsayılan değer Images'dir.

**Döndürür:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Görüntüleri kaydetmek için klasör adını belirler. Varsayılan değer Images'dir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Oluşturulan belgenin \\r (Macintosh), \\n (Unix) veya \\r\\n (Windows) satır sonlarını kullanıp kullanmayacağını belirtir. Varsayılan değer Unix'dir.

**Döndürür:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Oluşturulan belgenin \\r (Macintosh), \\n (Unix) veya \\r\\n (Windows) satır sonlarını kullanıp kullanmayacağını belirtir. Varsayılan değer Unix'dir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

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

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Sunumu dönüştürmek için markdown belirtimini belirler. Varsayılan değer Multi-markdown'dir.

**Döndürür:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Sunumu dönüştürmek için markdown belirtimini belirler. Varsayılan değer Multi-markdown'dir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır veya ayarlar. Biçim dizesi "\{0\}" yer tutucusunu içermelidir; bu, dışa aktarım sırasında slayt indeksine göre değiştirilir. Örnek: "\# Slide \{0\}" çıktısı "\# Slide 1", "\# Slide 2" gibi olacaktır.

**Döndürür:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır veya ayarlar. Biçim dizesi "\{0\}" yer tutucusunu içermelidir; bu, dışa aktarım sırasında slayt indeksine göre değiştirilir. Örnek: "\# Slide \{0\}" çıktısı "\# Slide 1", "\# Slide 2" gibi olacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Markdown dışa aktarımı sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirler. Bu özellik, ardışık boşlukların: - normal boşluk karakterleri olarak korunması, - normal boşluklar ve bölünmez boşluk varlıkları (�) arasında değişmesi, - veya tamamen (ilkinden sonra) bölünmez boşluk ile değiştirilerek Markdown çıktısında görsel hizalamanın korunması seçeneklerinden birini tanımlar. Varsayılan değer [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Döndürür:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Markdown dışa aktarımı sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirler. Bu özellik, ardışık boşlukların: - normal boşluk karakterleri olarak korunması, - normal boşluklar ve bölünmez boşluk varlıkları (�) arasında değişmesi, - veya tamamen (ilkinden sonra) bölünmez boşluk ile değiştirilerek Markdown çıktısında görsel hizalamanın korunması seçeneklerinden birini tanımlar. Varsayılan değer [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Doğru olarak ayarlanırsa, boş ya da sadece boşluk içeren satırları son Markdown çıktısından kaldırır. Varsayılan değer false'tur.

**Döndürür:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Doğru olarak ayarlanırsa, boş ya da sadece boşluk içeren satırları son Markdown çıktısından kaldırır. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Markdown dışa aktarımı sırasında SVG olmayan her görüntü (bitmap veya metafile) için gerçekleşir. Görüntünün nasıl kaydedileceği ve başvurulacağı özelleştirilebilir. İşlenmezse, görüntü yerel olarak göreli bir bağlantı ile kaydedilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown görüntü kaydetme olayı. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Markdown dışa aktarımı sırasında her SVG görüntü için gerçekleşir. Varsayılan kaydetme ve bağlantı oluşturma davranışı geçersiz kılınabilir. İşlenmezse, SVG yerel olarak göreli bir bağlantı ile kaydedilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG görüntü kaydetme olayı. |