---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html generator.
type: docs
url: /sv/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML-generator.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Lägger till formaterad HTML-text. |
| [addHtml(char[] html)](#addHtml-char---) | Lägger till formaterad HTML-text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Lägger till formaterad HTML-text. |
| [addText(String text)](#addText-java.lang.String-) | Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. |
| [addText(char[] text)](#addText-char---) | Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Citerar attributvärdet och lägger till det i HTML-filen. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Citerar attributvärdet och lägger till det i HTML-filen. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Citerar attributvärdet och lägger till det i HTML-filen. |
| [getSlideImageSize()](#getSlideImageSize--) | Returnerar bildstorlek för bilden. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Returnerar en enhet som bildstorlek för bilden anges i. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Returnerar en CSS-kod för enheten som bildstorlek för bilden anges i. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Returnerar index för föregående renderade bild eller -1 om den första bilden renderas. |
| [getSlideIndex()](#getSlideIndex--) | Returnerar index för bilden som för närvarande renderas. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Returnerar index för en bild som kommer att renderas efter den aktuella bilden eller -1 om den sista bilden för närvarande renderas. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Lägger till formaterad HTML-text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| html | java.lang.String | Text att lägga till. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Lägger till formaterad HTML-text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| html | char[] | Text att lägga till. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Lägger till formaterad HTML-text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| html | char[] | Text att lägga till. |
| startIndex | int | Startindex för den del som ska läggas till. |
| length | int | Längd på den del som ska läggas till. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att lägga till. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | char[] | Text att lägga till. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | char[] | Text att lägga till. |
| startIndex | int | Startindex för den del som ska läggas till. |
| length | int | Längd på den del som ska läggas till. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Citerar attributvärdet och lägger till det i HTML-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | Attributvärdesträng. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Citerar attributvärdet och lägger till det i HTML-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char[] | Attributvärdesträng. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Citerar attributvärdet och lägger till det i HTML-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char[] | Attributvärdesträng. |
| startIndex | int | Startindex för den del som ska läggas till. |
| length | int | Längd på den del som ska läggas till. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

Returnerar bildstorlek för bilden. Skrivskyddad [SizeF](../../com.aspose.slides.android/sizef).

**Returvärde:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Returnerar en enhet som bildstorlek för bilden anges i. Skrivskyddad [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Returvärde:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Returnerar en CSS-kod för enheten som bildstorlek för bilden anges i. Skrivskyddad String.

**Returvärde:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Returnerar index för föregående renderade bild eller -1 om den första bilden renderas. Skrivskyddad int.

**Returvärde:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Returnerar index för bilden som för närvarande renderas. Skrivskyddad int.

**Returvärde:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Returnerar index för en bild som kommer att renderas efter den aktuella bilden eller -1 om den sista bilden för närvarande renderas. Skrivskyddad int.

**Returvärde:**
int