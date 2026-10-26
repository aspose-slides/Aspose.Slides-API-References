---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html-Generator.
type: docs
url: /de/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
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
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Fügt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Fügt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Fügt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu. |
| [getSlideImageSize()](#getSlideImageSize--) | Gibt die Größe des Folienbildes zurück. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird. |
| [getSlideIndex()](#getSlideIndex--) | Gibt den Index der aktuell gerenderten Folie zurück. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn die aktuelle Folie die letzte ist. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | java.lang.String | Hinzuzufügender Text. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Fügt formatierten HTML-Text hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| html | char[] | Hinzuzufügender Text. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
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
public abstract void addText(String text)
```

Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Hinzuzufügender Text. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | char[] | Hinzuzufügender Text. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Fügt Klartext zu den HTML-Dateien hinzu und ersetzt Sonderzeichen durch HTML-Entitäten. Zeilenumbrüche und Leerzeichen werden nicht ersetzt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | char[] | Hinzuzufügender Text. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Fügt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | Zeichenkette des Attributwerts. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Fügt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char[] | Zeichenkette des Attributwerts. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Fügt Anführungszeichen um den Attributwert und fügt ihn zur HTML-Datei hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char[] | Zeichenkette des Attributwerts. |
| startIndex | int | Startindex des hinzuzufügenden Abschnitts. |
| length | int | Länge des hinzuzufügenden Abschnitts. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

Gibt die Größe des Folienbildes zurück. Nur lesend [SizeF](../../com.aspose.slides.android/sizef).

**Rückgabewert:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Gibt die Einheit zurück, in der die Folienbildgröße angegeben ist. Nur lesend [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Rückgabewert:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Gibt den CSS-Code der Einheit zurück, in der die Folienbildgröße angegeben ist. Nur lesend String.

**Rückgabewert:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Gibt den Index der zuvor gerenderten Folie zurück oder -1, wenn die erste Folie gerendert wird. Nur lesend int.

**Rückgabewert:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Gibt den Index der aktuell gerenderten Folie zurück. Nur lesend int.

**Rückgabewert:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Gibt den Index einer Folie zurück, die nach der aktuellen Folie gerendert wird, oder -1, wenn die aktuelle Folie die letzte ist. Nur lesend int.

**Rückgabewert:**
int