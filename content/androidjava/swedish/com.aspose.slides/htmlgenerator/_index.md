---
title: HtmlGenerator
second_title: Aspose.Slides för Android via Java API-referens
description: Html-generator.
type: docs
url: /sv/com.aspose.slides/htmlgenerator/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
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
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Citattecknar attributvärdet och lägger till det i HTML-filen. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Citattecknar attributvärdet och lägger till det i HTML-filen. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Citattecknar attributvärdet och lägger till det i HTML-filen. |
| [getSlideImageSize()](#getSlideImageSize--) | Returnerar bildstorlek för sliden. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Returnerar en enhet som bildstorleken för sliden anges i. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Returnerar en CSS-kod för enheten som bildstorleken för sliden anges i. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Returnerar index för föregående renderade slide eller -1 om den första sliden renderas. |
| [getSlideIndex()](#getSlideIndex--) | Returnerar index för den slide som för närvarande renderas. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Returnerar index för en slide som kommer att renderas efter den aktuella sliden eller -1 om den sista sliden renderas. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


Lägger till formaterad HTML-text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| html | java.lang.String | Text att lägga till. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


Lägger till formaterad HTML-text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| html | char[] | Text att lägga till. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


Lägger till formaterad HTML-text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| html | char[] | Text att lägga till. |
| startIndex | int | Startindex för delen som ska läggas till. |
| length | int | Längd på delen som ska läggas till. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text att lägga till. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | char[] | Text att lägga till. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


Lägger till vanlig text i HTML-filerna och ersätter specialtecken med HTML-entiteter. Radbrytningar och blanksteg ersätts inte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | char[] | Text att lägga till. |
| startIndex | int | Startindex för delen som ska läggas till. |
| length | int | Längd på delen som ska läggas till. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


Citattecknar attributvärdet och lägger till det i HTML-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | Sträng för attributvärde. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


Citattecknar attributvärdet och lägger till det i HTML-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char[] | Sträng för attributvärde. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


Citattecknar attributvärdet och lägger till det i HTML-filen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char[] | Sträng för attributvärde. |
| startIndex | int | Startindex för delen som ska läggas till. |
| length | int | Längd på delen som ska läggas till. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```


Returnerar bildstorlek för sliden. Skrivskyddad [SizeF](../../com.aspose.slides.android/sizef).

**Returnerar:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


Returnerar en enhet som bildstorleken för sliden anges i. Skrivskyddad [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Returnerar:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


Returnerar en CSS-kod för enheten som bildstorleken för sliden anges i. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


Returnerar index för föregående renderade slide eller -1 om den första sliden renderas. Skrivskyddad int.

**Returnerar:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Returnerar index för den slide som för närvarande renderas. Skrivskyddad int.

**Returnerar:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


Returnerar index för en slide som kommer att renderas efter den aktuella sliden eller -1 om den sista sliden renderas. Skrivskyddad int.

**Returnerar:**
int