---
title: HtmlGenerator
second_title: Aspose.Slides für Java API-Referenz
description: Html-Generator.
type: docs
url: /de/com.aspose.slides/htmlgenerator/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Html-Generator.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Fügt formatierten HTML-Text hinzu. |
| [addHtml(char[] html)](#addHtml-char---) | Fügt formatierten HTML-Text hinzu. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Fügt formatierten HTML-Text hinzu. |
| [addText(String text)](#addText-java.lang.String-) | Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addText(char[] text)](#addText-char---) | Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [getSlideImageSize()](#getSlideImageSize--) | Gibt die Größe des Folienbildes zurück. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird. |
| [getSlideIndex()](#getSlideIndex--) | Gibt den Index der aktuell gerenderten Folie zurück. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn die letzte Folie gerade gerendert wird. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | java.lang.String | Hinzu zuzufügender Text. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | char[] | Hinzu zuzufügender Text. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | char[] | Hinzu zuzufügender Text. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Hinzu zuzufügender Text. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | char[] | Hinzu zuzufügender Text. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | char[] | Hinzu zuzufügender Text. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | Zeichenkette des Attributwertes. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char[] | Zeichenkette des Attributwertes. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char[] | Zeichenkette des Attributwertes. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```


Gibt die Größe des Folienbildes zurück. Nur lesend java.awt.geom.Dimension2D.

**Rückgabewert:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSize()
```


Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist. Nur lesend [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Rückgabewert:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist. Nur lesend String.

**Rückgabewert:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird. Nur lesend int.

**Rückgabewert:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Gibt den Index der aktuell gerenderten Folie zurück. Nur lesend int.

**Rückgabewert:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn die letzte Folie gerade gerendert wird. Nur lesend int.

**Rückgabewert:**
int