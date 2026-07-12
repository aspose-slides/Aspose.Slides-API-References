---
title: HtmlGenerator
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Html üreticisi.
type: docs
url: /tr/com.aspose.slides/htmlgenerator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Html üreteci.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Biçimlendirilmiş HTML metni ekler. |
| [addHtml(char[] html)](#addHtml-char---) | Biçimlendirilmiş HTML metni ekler. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Biçimlendirilmiş HTML metni ekler. |
| [addText(String text)](#addText-java.lang.String-) | Html dosyalarına düz metin ekler, özel karakterleri html varlıklarıyla değiştirir. |
| [addText(char[] text)](#addText-char---) | Html dosyalarına düz metin ekler, özel karakterleri html varlıklarıyla değiştirir. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Html dosyalarına düz metin ekler, özel karakterleri html varlıklarıyla değiştirir. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Öznitelik değerini tırnak içine alır ve html dosyasına ekler. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Öznitelik değerini tırnak içine alır ve html dosyasına ekler. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Öznitelik değerini tırnak içine alır ve html dosyasına ekler. |
| [getSlideImageSize()](#getSlideImageSize--) | Slayt görüntü boyutunu döndürür. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Slayt görüntü boyutunun belirtildiği birimi döndürür. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Slayt görüntü boyutunun belirtildiği birimin css kodunu döndürür. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Önceden işlenmiş slaytın indeksini döndürür veya ilk slayt işleniyorsa -1 döndürür. |
| [getSlideIndex()](#getSlideIndex--) | Şu anda işlenen slaytın indeksini döndürür. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Mevcut slayttan sonra işlenecek slaytın indeksini döndürür veya son slayt işleniyorsa -1 döndürür. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Biçimlendirilmiş HTML metni ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| html | java.lang.String | Eklenecek metin. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Biçimlendirilmiş HTML metni ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| html | char[] | Eklenecek metin. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Biçimlendirilmiş HTML metni ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| html | char[] | Eklenecek metin. |
| startIndex | int | Eklenecek kısmın başlangıç indeksi. |
| length | int | Eklenecek kısmın uzunluğu. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Html dosyalarına düz metin ekler, özel karakterleri html varlıklarıyla değiştirir. Satır sonları ve boşluklar değiştirilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Eklenecek metin. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Html dosyalarına düz metin ekler, özel karakterleri html varlıklarıyla değiştirir. Satır sonları ve boşluklar değiştirilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | char[] | Eklenecek metin. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Html dosyalarına düz metin ekler, özel karakterleri html varlıklarıyla değiştirir. Satır sonları ve boşluklar değiştirilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | char[] | Eklenecek metin. |
| startIndex | int | Eklenecek kısmın başlangıç indeksi. |
| length | int | Eklenecek kısmın uzunluğu. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Öznitelik değerini tırnak içine alır ve html dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Öznitelik değeri dizesi. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Öznitelik değerini tırnak içine alır ve html dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char[] | Öznitelik değeri dizesi. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Öznitelik değerini tırnak içine alır ve html dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char[] | Öznitelik değeri dizesi. |
| startIndex | int | Eklenecek kısmın başlangıç indeksi. |
| length | int | Eklenecek kısmın uzunluğu. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

Slayt görüntü boyutunu döndürür. Yalnızca okuma [SizeF](../../com.aspose.slides.android/sizef).

**Döndürür:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Slayt görüntü boyutunun belirtildiği birimi döndürür. Yalnızca okuma [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Döndürür:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Slayt görüntü boyutunun belirtildiği birimin css kodunu döndürür. Yalnızca okuma String.

**Döndürür:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Önceden işlenmiş slaytın indeksini döndürür veya ilk slayt işleniyorsa -1 döndürür. Yalnızca okuma int.

**Döndürür:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Şu anda işlenen slaytın indeksini döndürür. Yalnızca okuma int.

**Döndürür:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Mevcut slayttan sonra işlenecek slaytın indeksini döndürür veya son slayt işleniyorsa -1 döndürür. Yalnızca okuma int.

**Döndürür:**
int