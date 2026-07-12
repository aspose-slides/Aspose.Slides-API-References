---
title: PatternFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein Muster zum Füllen einer Form dar.
type: docs
url: /de/com.aspose.slides/patternformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Stellt ein Muster zum Füllen einer Form dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Gibt den Musterstil zurück oder legt ihn fest. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Gibt den Musterstil zurück oder legt ihn fest. |
| [getForeColor()](#getForeColor--) | Gibt die Vordergrundfarbe des Musters zurück. |
| [getBackColor()](#getBackColor--) | Gibt die Hintergrundfarbe des Musters zurück. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Erstellt ein Kachelbild für die Musterfüllung. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesbar long.

**Rückgabe:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Gibt den Musterstil zurück oder legt ihn fest. Lesen/Schreiben [PatternStyle](../../com.aspose.slides/patternstyle).

**Rückgabe:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Gibt den Musterstil zurück oder legt ihn fest. Lesen/Schreiben [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Gibt die Vordergrundfarbe des Musters zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Gibt die Hintergrundfarbe des Musters zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```


Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| background | java.lang.Integer | Der Hintergrund java.lang.Integer für das Muster. |
| foreground | java.lang.Integer | Der Vordergrund java.lang.Integer für das Muster. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Kachel [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```


Erstellt ein Kachelbild für die Musterfüllung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleColor | java.lang.Integer | Der Standard java.lang.Integer |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Kachel [IImage](../../com.aspose.slides/iimage).