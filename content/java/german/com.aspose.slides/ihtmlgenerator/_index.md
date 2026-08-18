---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: HTML-Generator.
type: docs
url: /de/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML-Generator.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Fügt formatierten HTML-Text hinzu. |
| [addHtml(char[] html)](#addHtml-char---) | Fügt formatierten HTML-Text hinzu. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Fügt formatierten HTML-Text hinzu. |
| [addText(String text)](#addText-java.lang.String-) | Fügt reinen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addText(char[] text)](#addText-char---) | Fügt reinen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Fügt reinen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [getSlideImageSize()](#getSlideImageSize--) | Gibt die Größe des Folienbildes zurück. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird. |
| [getSlideIndex()](#getSlideIndex--) | Gibt den Index der gerade gerenderten Folie zurück. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn die aktuelle Folie die letzte ist. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | java.lang.String | Text, der hinzugefügt werden soll. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | char[] | Text, der hinzugefügt werden soll. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | char[] | Text, der hinzugefügt werden soll. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Fügt reinen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text, der hinzugefügt werden soll. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Fügt reinen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | char[] | Text, der hinzugefügt werden soll. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Fügt reinen Text zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | char[] | Text, der hinzugefügt werden soll. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | String mit Attributwert. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char[] | String mit Attributwert. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Setzt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char[] | String mit Attributwert. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

Gibt die Größe des Folienbildes zurück. Nur lesbar java.awt.geom.Dimension2D.

**Rückgabe:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist. Nur lesbar [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Rückgabe:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist. Nur lesbar String.

**Rückgabe:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird. Nur lesbar int.

**Rückgabe:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Gibt den Index der gerade gerenderten Folie zurück. Nur lesbar int.

**Rückgabe:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn die aktuelle Folie die letzte ist. Nur lesbar int.

**Rückgabe:**
int