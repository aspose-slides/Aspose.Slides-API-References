---
title: HtmlGenerator
second_title: Aspose.Slides for Java API Referansı
description: Html oluşturucu.
type: docs
url: /tr/com.aspose.slides/htmlgenerator/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Html oluşturucu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Biçimlendirilmiş HTML metni ekler. |
| [addHtml(char[] html)](#addHtml-char---) | Biçimlendirilmiş HTML metni ekler. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Biçimlendirilmiş HTML metni ekler. |
| [addText(String text)](#addText-java.lang.String-) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. |
| [addText(char[] text)](#addText-char---) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Öznitelik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Öznitelik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Öznitelik değerini tırnak içine alır ve HTML dosyasına ekler. |
| [getSlideImageSize()](#getSlideImageSize--) | Slayt görüntüsü boyutunu döndürür. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Slayt görüntüsü boyutunun belirtildiği birimi döndürür. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Slayt görüntüsü boyutunun belirtildiği birimin css kodunu döndürür. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Önceden işlenen slaydın indeksini döndürür veya ilk slayt işleniyorsa -1 döner. |
| [getSlideIndex()](#getSlideIndex--) | Şu anda işlenen slaydın indeksini döndürür. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Mevcut slayttan sonra işlenecek slaydın indeksini döndürür veya son slayt işleniyorsa -1 döner. |
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


HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. Satır sonları ve boşluk karakterleri değiştirilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Eklenecek metin. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. Satır sonları ve boşluk karakterleri değiştirilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | char[] | Eklenecek metin. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. Satır sonları ve boşluk karakterleri değiştirilmez.

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


Öznitelik değerini tırnak içine alır ve HTML dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Öznitelik değeri dizesi. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


Öznitelik değerini tırnak içine alır ve HTML dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char[] | Öznitelik değeri dizesi. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


Öznitelik değerini tırnak içine alır ve HTML dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char[] | Öznitelik değeri dizesi. |
| startIndex | int | Eklenecek kısmın başlangıç indeksi. |
| length | int | Eklenecek kısmın uzunluğu. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```


Slayt görüntüsü boyutunu döndürür. Salt okunur java.awt.geom.Dimension2D.

**Döndürür:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


Slayt görüntüsü boyutunun belirtildiği birimi döndürür. Salt okunur [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Döndürür:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


Slayt görüntüsü boyutunun belirtildiği birimin css kodunu döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


Önceden işlenen slaydın indeksini döndürür veya ilk slayt işleniyorsa -1 döner. Salt okunur int.

**Döndürür:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Şu anda işlenen slaydın indeksini döndürür. Salt okunur int.

**Döndürür:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


Mevcut slayttan sonra işlenecek slaydın indeksini döndürür veya son slayt işleniyorsa -1 döner. Salt okunur int.

**Döndürür:**
int