---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Android için Java API Referansı
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
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExportType()](#getExportType--) | Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. |
| [setExportType(int value)](#setExportType-int-) | Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. |
| [getBasePath()](#getBasePath--) | Kaynaklarla birlikte belgenin kaydedileceği temel yolu belirtir. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Kaynaklarla birlikte belgenin kaydedileceği temel yolu belirtir. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Görüntülerin kaydedileceği klasör adını belirtir. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Görüntülerin kaydedileceği klasör adını belirtir. |
| [getNewLineType()](#getNewLineType--) | Oluşturulan belgenin \\r(Macintosh), \\n(Unix) veya \\r\\n(Windows) yeni satır karakterlerine sahip olup olmayacağını belirtir. |
| [setNewLineType(int value)](#setNewLineType-int-) | Oluşturulan belgenin \\r(Macintosh), \\n(Unix) veya \\r\\n(Windows) yeni satır karakterlerine sahip olup olmayacağını belirtir. |
| [getShowComments()](#getShowComments--) | Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. |
| [getFlavor()](#getFlavor--) | Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. |
| [setFlavor(int value)](#setFlavor-int-) | Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır veya ayarlar. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır veya ayarlar. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Markdown dışa aktarma sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirtir. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Markdown dışa aktarma sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirtir. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | true olarak ayarlanırsa, son Markdown çıktısından boş veya yalnızca boşluk içeren satırlar kaldırılır. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | true olarak ayarlanırsa, son Markdown çıktısından boş veya yalnızca boşluk içeren satırlar kaldırılır. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Markdown dışa aktarma sırasında her SVG olmayan görüntü (bitmap veya metafile) için gerçekleşir. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Markdown dışa aktarma sırasında her SVG görüntüsü için gerçekleşir. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Yapıcı.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. Varsayılan **TextOnly**dır.

**Döndürür:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. Varsayılan **TextOnly**dır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Kaynaklarla birlikte belgenin kaydedileceği temel yolu belirtir. Varsayılan uygulamanın geçerli dizinidir.

**Döndürür:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Kaynaklarla birlikte belgenin kaydedileceği temel yolu belirtir. Varsayılan uygulamanın geçerli dizinidir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Görüntülerin kaydedileceği klasör adını belirtir. Varsayılan **Images**tir.

**Döndürür:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Görüntülerin kaydedileceği klasör adını belirtir. Varsayılan **Images**tir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Oluşturulan belgenin \\r(Macintosh), \\n(Unix) veya \\r\\n(Windows) yeni satır karakterlerine sahip olup olmayacağını belirtir. Varsayılan **Unix**tir.

**Döndürür:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Oluşturulan belgenin \\r(Macintosh), \\n(Unix) veya \\r\\n(Windows) yeni satır karakterlerine sahip olup olmayacağını belirtir. Varsayılan **Unix**tir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. Varsayılan false’tur.

**Döndürür:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. Varsayılan false’tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan false’tur.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan false’tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. Varsayılan false’tur.

**Döndürür:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. Varsayılan false’tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. Varsayılan **Multi-markdown**dır.

**Döndürür:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. Varsayılan **Multi-markdown**dır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır veya ayarlar. Biçim dizesi \"\\{0\\}\" yer tutucusunu içermelidir; bu, dışa aktarma sırasında slayt indeksine göre değiştirilir. Örnek: \"\\# Slide \\{0\\}\" çıktıda \"\\# Slide 1\", \"\\# Slide 2\" vb. üretir.

**Döndürür:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır veya ayarlar. Biçim dizesi \"\\{0\\}\" yer tutucusunu içermelidir; bu, dışa aktarma sırasında slayt indeksine göre değiştirilir. Örnek: \"\\# Slide \\{0\\}\" çıktıda \"\\# Slide 1\", \"\\# Slide 2\" vb. üretir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


Markdown dışa aktarma sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirtir. Bu özellik, art arda gelen boşlukların: - normal boşluk karakterleri olarak korunması, - normal boşluklarla kırılmaz boşluk varlıkları (�) arasında dönüşümlü olması, - ya da görsel hizalamayı korumak için (ilkinden sonra) kırılmaz boşlukla tamamen değiştirilmesi seçeneklerini tanımlar. Varsayılan değer [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)dir.

**Döndürür:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


Markdown dışa aktarma sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirtir. Bu özellik, art arda gelen boşlukların: - normal boşluk karakterleri olarak korunması, - normal boşluklarla kırılmaz boşluk varlıkları (�) arasında dönüşümlü olması, - ya da görsel hizalamayı korumak için (ilkinden sonra) kırılmaz boşlukla tamamen değiştirilmesi seçeneklerini tanımlar. Varsayılan değer [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)dir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


True olarak ayarlanırsa, son Markdown çıktısından boş veya yalnızca boşluk içeren satırlar kaldırılır. Varsayılan false’tur.

**Döndürür:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


True olarak ayarlanırsa, son Markdown çıktısından boş veya yalnızca boşluk içeren satırlar kaldırılır. Varsayılan false’tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


Markdown dışa aktarma sırasında her SVG olmayan görüntü (bitmap veya metafile) için gerçekleşir. Görüntünün nasıl kaydedileceği ve referans verileceği özelleştirilebilir. İşlenmezse, görüntü yerel olarak göreceli bir bağlantıyla kaydedilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown görüntü kaydetme olayı. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


Markdown dışa aktarma sırasında her SVG görüntüsü için gerçekleşir. Varsayılan kaydetme ve bağlantı oluşturma işlemi geçersiz kılınabilir. İşlenmezse, SVG yerel olarak göreceli bir bağlantıyla kaydedilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG görüntü kaydetme olayı. |
