---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html generator.
type: docs
url: /nl/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Html-generator.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Voegt geformatteerde HTML-tekst toe. |
| [addHtml(char[] html)](#addHtml-char---) | Voegt geformatteerde HTML-tekst toe. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Voegt geformatteerde HTML-tekst toe. |
| [addText(String text)](#addText-java.lang.String-) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addText(char[] text)](#addText-char---) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Zet aanhalingstekens rond attribuutwaarde en voegt die toe aan het html-bestand. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Zet aanhalingstekens rond attribuutwaarde en voegt die toe aan het html-bestand. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Zet aanhalingstekens rond attribuutwaarde en voegt die toe aan het html-bestand. |
| [getSlideImageSize()](#getSlideImageSize--) | Retourneert de grootte van de slide-afbeelding. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Retourneert een eenheid waarin de grootte van de slide-afbeelding wordt gespecificeerd. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Retourneert een css-code van eenheid waarin de grootte van de slide-afbeelding wordt gespecificeerd. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Retourneert de index van de eerder gerenderde slide of -1 als de eerste slide wordt gerenderd. |
| [getSlideIndex()](#getSlideIndex--) | Retourneert de index van de momenteel renderende slide. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Retourneert de index van een slide die na de huidige slide wordt gerenderd, of -1 als de momenteel renderende slide de laatste is. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Voegt geformatteerde HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | java.lang.String | Tekst die moet worden toegevoegd. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Voegt geformatteerde HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | char[] | Tekst die moet worden toegevoegd. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Voegt geformatteerde HTML-tekst toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| html | char[] | Tekst die moet worden toegevoegd. |
| startIndex | int | Beginindex van het toe te voegen gedeelte. |
| length | int | Lengte van het toe te voegen gedeelte. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en witruimtes worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst die moet worden toegevoegd. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en witruimtes worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | char[] | Tekst die moet worden toegevoegd. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Voegt platte tekst toe aan de html-bestanden, waarbij speciale tekens worden vervangen door html-entiteiten. Regeleinden en witruimtes worden niet vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | char[] | Tekst die moet worden toegevoegd. |
| startIndex | int | Beginindex van het toe te voegen gedeelte. |
| length | int | Lengte van het toe te voegen gedeelte. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Zet aanhalingstekens rond attribuutwaarde en voegt die toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | String met attribuutwaarde. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Zet aanhalingstekens rond attribuutwaarde en voegt die toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char[] | String met attribuutwaarde. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Zet aanhalingstekens rond attribuutwaarde en voegt die toe aan het html-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char[] | String met attribuutwaarde. |
| startIndex | int | Beginindex van het toe te voegen gedeelte. |
| length | int | Lengte van het toe te voegen gedeelte. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

Retourneert de grootte van de slide-afbeelding. Alleen-lezen java.awt.geom.Dimension2D.

**Retour:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Retourneert een eenheid waarin de grootte van de slide-afbeelding wordt gespecificeerd. Alleen-lezen [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Retour:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Retourneert een css-code van eenheid waarin de grootte van de slide-afbeelding wordt gespecificeerd. Alleen-lezen String.

**Retour:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Retourneert de index van de eerder gerenderde slide of -1 als de eerste slide wordt gerenderd. Alleen-lezen int.

**Retour:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Retourneert de index van de momenteel renderende slide. Alleen-lezen int.

**Retour:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Retourneert de index van een slide die na de huidige slide wordt gerenderd, of -1 als de momenteel renderende slide de laatste is. Alleen-lezen int.

**Retour:**
int