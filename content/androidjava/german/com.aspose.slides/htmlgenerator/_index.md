---
title: HtmlGenerator
second_title: Aspose.Slides für Android über Java API Referenz
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
| [addText(String text)](#addText-java.lang.String-) | Fügt einfachen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addText(char[] text)](#addText-char---) | Fügt einfachen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Fügt einfachen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [getSlideImageSize()](#getSlideImageSize--) | Gibt die Größe des Folienbildes zurück. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird. |
| [getSlideIndex()](#getSlideIndex--) | Gibt den Index der aktuell rendernden Folie zurück. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn gerade die letzte Folie gerendert wird. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | java.lang.String | Hinzuzufügender Text. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | char[] | Hinzuzufügender Text. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | char[] | Hinzuzufügender Text. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Fügt einfachen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Hinzuzufügender Text. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Fügt einfachen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | char[] | Hinzuzufügender Text. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Fügt einfachen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | char[] | Hinzuzufügender Text. |
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
public final SizeF getSlideImageSize()
```

Gibt die Größe des Folienbildes zurück. Nur lesbar [SizeF](../../com.aspose.slides.android/sizef).

**Rückgabe:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist. Nur lesbar [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Rückgabe:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist. Nur lesbar String.

**Rückgabe:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird. Nur lesbar int.

**Rückgabe:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Gibt den Index der aktuell rendernden Folie zurück. Nur lesbar int.

**Rückgabe:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn gerade die letzte Folie gerendert wird. Nur lesbar int.

**Rückgabe:**
int