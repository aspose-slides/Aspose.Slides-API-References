---
title: HtmlGenerator
second_title: Aspose.Slides voor Android via Java API-referentie
description: HTML-generator.
type: docs
url: /nl/com.aspose.slides/htmlgenerator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Html-generator.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Voegt opgemaakte HTML-tekst toe. |
| [addHtml(char[] html)](#addHtml-char---) | Voegt opgemaakte HTML-tekst toe. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Voegt opgemaakte HTML-tekst toe. |
| [addText(String text)](#addText-java.lang.String-) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addText(char[] text)](#addText-char---) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Citeert attribuutwaarde en voegt deze toe aan het html-bestand. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Citeert attribuutwaarde en voegt deze toe aan het html-bestand. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Citeert attribuutwaarde en voegt deze toe aan het html-bestand. |
| [getSlideImageSize()](#getSlideImageSize--) | Retourneert de grootte van de dia-afbeelding. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Retourneert een eenheid waarin de grootte van de dia-afbeelding is gespecificeerd. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Retourneert een css-code van de eenheid waarin de grootte van de dia-afbeelding is gespecificeerd. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Retourneert de index van de eerder gerenderde dia of -1 als de eerste dia wordt gerenderd. |
| [getSlideIndex()](#getSlideIndex--) | Retourneert de index van de momenteel renderende dia. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Retourneert de index van een dia die na de huidige dia wordt gerenderd of -1 als de huidige dia de laatste is. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Voegt opgemaakte HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | java.lang.String | Tekst om toe te voegen. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Voegt opgemaakte HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | char[] | Tekst om toe te voegen. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Voegt opgemaakte HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | char[] | Tekst om toe te voegen. |
| startIndex | int | Beginindex van het toe te voegen gedeelte. |
| length | int | Lengte van het toe te voegen gedeelte. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en spaties worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst om toe te voegen. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en spaties worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | char[] | Tekst om toe te voegen. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en spaties worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | char[] | Tekst om toe te voegen. |
| startIndex | int | Beginindex van het toe te voegen gedeelte. |
| length | int | Lengte van het toe te voegen gedeelte. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Citeert attribuutwaarde en voegt deze toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | String met attribuutwaarde. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Citeert attribuutwaarde en voegt deze toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char[] | String met attribuutwaarde. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Citeert attribuutwaarde en voegt deze toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char[] | String met attribuutwaarde. |
| startIndex | int | Beginindex van het toe te voegen gedeelte. |
| length | int | Lengte van het toe te voegen gedeelte. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

Retourneert de grootte van de dia-afbeelding. Alleen-lezen [SizeF](../../com.aspose.slides.android/sizef).

**Retour:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Retourneert een eenheid waarin de grootte van de dia-afbeelding is gespecificeerd. Alleen-lezen [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Retour:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Retourneert een css-code van de eenheid waarin de grootte van de dia-afbeelding is gespecificeerd. Alleen-lezen String.

**Retour:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Retourneert de index van de eerder gerenderde dia of -1 als de eerste dia wordt gerenderd. Alleen-lezen int.

**Retour:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Retourneert de index van de momenteel renderende dia. Alleen-lezen int.

**Retour:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Retourneert de index van een dia die na de huidige dia wordt gerenderd of -1 als de huidige dia de laatste is. Alleen-lezen int.

**Retour:**
int