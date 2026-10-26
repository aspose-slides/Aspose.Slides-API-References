---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html-generator.
type: docs
url: /sv/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Html-generator.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Lägger till formaterad HTML-text. |
| [addHtml(char[] html)](#addHtml-char---) | Lägger till formaterad HTML-text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Lägger till formaterad HTML-text. |
| [addText(String text)](#addText-java.lang.String-) | Lägger till vanlig text i html-filerna och ersätter specialtecken med html-entiteter. |
| [addText(char[] text)](#addText-char---) | Lägger till vanlig text i html-filerna och ersätter specialtecken med html-entiteter. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Lägger till vanlig text i html-filerna och ersätter specialtecken med html-entiteter. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Citerar attributvärde och lägger till det i html-filen. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Citerar attributvärde och lägger till det i html-filen. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Citerar attributvärde och lägger till det i html-filen. |
| [getSlideImageSize()](#getSlideImageSize--) | Returnerar bildstorlek för bilden. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Returnerar en enhet som bildstorlek för bilden är angiven i. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Returnerar en css-kod för enheten som bildstorlek för bilden är angiven i. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Returnerar index för föregående renderade bild eller -1 om den första bilden renderas. |
| [getSlideIndex()](#getSlideIndex--) | Returnerar index för den bild som för närvarande renderas. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Returnerar index för en bild som kommer att renderas efter den aktuella bilden eller -1 om den aktuella bilden är den sista. |
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
| length | int | Längd för den del som ska läggas till. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Lägger till vanlig text i html-filerna och ersätter specialtecken med html-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att lägga till. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Lägger till vanlig text i html-filerna och ersätter specialtecken med html-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | char[] | Text att lägga till. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Lägger till vanlig text i html-filerna och ersätter specialtecken med html-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | char[] | Text att lägga till. |
| startIndex | int | Startindex för den del som ska läggas till. |
| length | int | Längd för den del som ska läggas till. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Citerar attributvärde och lägger till det i html-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | Sträng för attributvärde. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Citerar attributvärde och lägger till det i html-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char[] | Sträng för attributvärde. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Citerar attributvärde och lägger till det i html-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char[] | Sträng för attributvärde. |
| startIndex | int | Startindex för den del som ska läggas till. |
| length | int | Längd för den del som ska läggas till. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

Returnerar bildstorlek för bilden. Skrivskyddad java.awt.geom.Dimension2D.

**Returnerar:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Returnerar en enhet som bildstorlek för bilden är angiven i. Skrivskyddad [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Returnerar:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Returnerar en css-kod för enheten som bildstorlek för bilden är angiven i. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Returnerar index för föregående renderade bild eller -1 om den första bilden renderas. Skrivskyddad int.

**Returnerar:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Returnerar index för den bild som för närvarande renderas. Skrivskyddad int.

**Returnerar:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Returnerar index för en bild som kommer att renderas efter den aktuella bilden eller -1 om den aktuella bilden är den sista. Skrivskyddad int.

**Returnerar:**
int