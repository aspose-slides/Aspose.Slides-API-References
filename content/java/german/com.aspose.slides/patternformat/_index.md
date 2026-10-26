---
title: PatternFormat
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein Muster dar, um eine Form zu füllen.
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

Stellt ein Muster dar, um eine Form zu füllen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Gibt den Musterstil zurück oder setzt ihn. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Gibt den Musterstil zurück oder setzt ihn. |
| [getForeColor()](#getForeColor--) | Gibt die Vordergrundfarbe des Musters zurück. |
| [getBackColor()](#getBackColor--) | Gibt die Hintergrundfarbe des Musters zurück. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Erstellt ein Kachelbild für die Musterfüllung. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesend long.

**Rückgabe:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Gibt den Musterstil zurück oder setzt ihn. Lese/Schreib [PatternStyle](../../com.aspose.slides/patternstyle).

**Rückgabe:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Gibt den Musterstil zurück oder setzt ihn. Lese/Schreib [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Gibt die Vordergrundfarbe des Musters zurück. Nur lesend [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Gibt die Hintergrundfarbe des Musters zurück. Nur lesend [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| background | java.awt.Color | Die Hintergrund java.awt.Color für das Muster. |
| foreground | java.awt.Color | Die Vordergrund java.awt.Color für das Muster. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Kachel [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Erstellt ein Kachelbild für die Musterfüllung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleColor | java.awt.Color | Die Standard java.awt.Color |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Kachel [IImage](../../com.aspose.slides/iimage).