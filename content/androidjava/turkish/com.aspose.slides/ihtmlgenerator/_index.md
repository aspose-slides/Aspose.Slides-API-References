---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: HTML üreticisi.
type: docs
url: /tr/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML üreticisi.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Adds formatted HTML text. |
| [addHtml(char[] html)](#addHtml-char---) | Adds formatted HTML text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Adds formatted HTML text. |
| [addText(String text)](#addText-java.lang.String-) | Adds plain text to the html files, replacing special characters with html entities. |
| [addText(char[] text)](#addText-char---) | Adds plain text to the html files, replacing special characters with html entities. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Adds plain text to the html files, replacing special characters with html entities. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Quotes attribute value and adds it to the html file. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Quotes attribute value and adds it to the html file. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Quotes attribute value and adds it to the html file. |
| [getSlideImageSize()](#getSlideImageSize--) | Returns slide image size. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Returns a unit in which slide image size is specified. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Returns a css code of unit in which slide image size is specified. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Returns index of previously rendered slide or -1 if first slide is rendering. |
| [getSlideIndex()](#getSlideIndex--) | Returns index of currently rendering slide. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Biçimlendirilmiş HTML metni ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| html | java.lang.String | Eklenecek metin. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Biçimlendirilmiş HTML metni ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| html | char[] | Eklenecek metin. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Biçimlendirilmiş HTML metni ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| html | char[] | Eklenecek metin. |
| startIndex | int | Eklenecek kısmın başlangıç dizini. |
| length | int | Eklenecek kısmın uzunluğu. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. Satır sonları ve boşluk karakterleri değiştirilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Eklenecek metin. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. Satır sonları ve boşluk karakterleri değiştirilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | char[] | Eklenecek metin. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

HTML dosyalarına düz metin ekler, özel karakterleri HTML varlıklarıyla değiştirir. Satır sonları ve boşluk karakterleri değiştirilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | char[] | Eklenecek metin. |
| startIndex | int | Eklenecek kısmın başlangıç dizini. |
| length | int | Eklenecek kısmın uzunluğu. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Özellik değerini tırnak içine alır ve HTML dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Özellik değeri dizesi. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Özellik değerini tırnak içine alır ve HTML dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char[] | Özellik değeri dizesi. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Özellik değerini tırnak içine alır ve HTML dosyasına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char[] | Özellik değeri dizesi. |
| startIndex | int | Eklenecek kısmın başlangıç dizini. |
| length | int | Eklenecek kısmın uzunluğu. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

Sunum slaytının görüntü boyutunu döndürür. Yalnızca okuma [SizeF](../../com.aspose.slides.android/sizef).

**Döndürür:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Sunum slaytının görüntü boyutunun belirtildiği birimi döndürür. Yalnızca okuma [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Döndürür:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Sunum slaytının görüntü boyutunun belirtildiği birimin CSS kodunu döndürür. Yalnızca okuma String.

**Döndürür:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Önceden render edilen slaydın indeksini döndürür veya ilk slayt render ediliyorsa -1 döndürür. Yalnızca okuma int.

**Döndürür:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Şu anda render edilen slaydın indeksini döndürür. Yalnızca okuma int.

**Döndürür:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Mevcut slayttan sonra render edilecek bir slaydın indeksini döndürür veya son slayt render ediliyorsa -1 döndürür. Yalnızca okuma int.

**Döndürür:**
int