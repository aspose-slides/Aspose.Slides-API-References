---
title: HtmlGenerator
second_title: Aspose.Slides voor Java API-referentie
description: Html-generator.
type: docs
url: /nl/com.aspose.slides/htmlgenerator/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

HTML-generator.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Voegt geformatteerde HTML-tekst toe. |
| [addHtml(char[] html)](#addHtml-char---) | Voegt geformatteerde HTML-tekst toe. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Voegt geformatteerde HTML-tekst toe. |
| [addText(String text)](#addText-java.lang.String-) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addText(char[] text)](#addText-char---) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Zet aanhalingstekens om de attribuutwaarde en voegt deze toe aan het html-bestand. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Zet aanhalingstekens om de attribuutwaarde en voegt deze toe aan het html-bestand. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Zet aanhalingstekens om de attribuutwaarde en voegt deze toe aan het html-bestand. |
| [getSlideImageSize()](#getSlideImageSize--) | Retourneert de grootte van de dia-afbeelding. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Retourneert een eenheid waarin de grootte van de dia-afbeelding is gespecificeerd. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Retourneert een CSS-code van de eenheid waarin de grootte van de dia-afbeelding is gespecificeerd. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Retourneert de index van de eerder gerenderde dia of -1 indien de eerste dia wordt gerenderd. |
| [getSlideIndex()](#getSlideIndex--) | Retourneert de index van de momenteel renderende dia. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Retourneert de index van een dia die wordt gerenderd na de huidige dia of -1 indien de huidige dia de laatste is. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Voegt geformatteerde HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | java.lang.String | Tekst om toe te voegen. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Voegt geformatteerde HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | char[] | Tekst om toe te voegen. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Voegt geformatteerde HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | char[] | Tekst om toe te voegen. |
| startIndex | int | Startindex van het gedeelte dat moet worden toegevoegd. |
| length | int | Lengte van het toe te voegen gedeelte. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en witruimtes worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst om toe te voegen. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en witruimtes worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | char[] | Tekst om toe te voegen. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en witruimtes worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | char[] | Tekst om toe te voegen. |
| startIndex | int | Startindex van het gedeelte dat moet worden toegevoegd. |
| length | int | Lengte van het toe te voegen gedeelte. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Zet aanhalingstekens om de attribuutwaarde en voegt deze toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | Attribuutwaarde. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Zet aanhalingstekens om de attribuutwaarde en voegt deze toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char[] | Attribuutwaarde. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Zet aanhalingstekens om de attribuutwaarde en voegt deze toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char[] | Attribuutwaarde. |
| startIndex | int | Startindex van het gedeelte dat moet worden toegevoegd. |
| length | int | Lengte van het toe te voegen gedeelte. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

Retourneert de grootte van de dia-afbeelding. Alleen-lezen java.awt.geom.Dimension2D.

**Retourneert:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Retourneert een eenheid waarin de grootte van de dia-afbeelding is gespecificeerd. Alleen-lezen [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Retourneert:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Retourneert een CSS-code van de eenheid waarin de grootte van de dia-afbeelding is gespecificeerd. Alleen-lezen String.

**Retourneert:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Retourneert de index van de eerder gerenderde dia of -1 indien de eerste dia wordt gerenderd. Alleen-lezen int.

**Retourneert:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Retourneert de index van de momenteel renderende dia. Alleen-lezen int.

**Retourneert:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Retourneert de index van een dia die wordt gerenderd na de huidige dia of -1 indien de huidige dia de laatste is. Alleen-lezen int.

**Retourneert:**
int