---
title: IPatternFormat
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt ein Muster dar, um eine Form zu füllen.
type: docs
url: /de/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Stellt ein Muster dar, um eine Form zu füllen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Gibt den PatternStyle zurück oder legt ihn fest. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Gibt den PatternStyle zurück oder legt ihn fest. |
| [getForeColor()](#getForeColor--) | Gibt die Vordergrund-Patternfarbe zurück. |
| [getBackColor()](#getBackColor--) | Gibt die Hintergrund-Patternfarbe zurück. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Erstellt ein Kachelbild für die Pattern-Füllung mit angegebenen Farben. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Erstellt ein Kachelbild für die Pattern-Füllung. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Gibt den PatternStyle zurück oder legt ihn fest. Lesen/Schreiben [PatternStyle](../../com.aspose.slides/patternstyle).

**Rückgabewert:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Gibt den PatternStyle zurück oder legt ihn fest. Lesen/Schreiben [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Gibt die Vordergrund-Patternfarbe zurück. Nur lesend [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Gibt die Hintergrund-Patternfarbe zurück. Nur lesend [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Erstellt ein Kachelbild für die Pattern-Füllung mit angegebenen Farben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| background | java.lang.Integer | Der Hintergrund java.lang.Integer für das Muster. |
| foreground | java.lang.Integer | Der Vordergrund java.lang.Integer für das Muster. |

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Kachel android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Erstellt ein Kachelbild für die Pattern-Füllung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleColor | java.lang.Integer | Der Standard java.lang.Integer, definiert im StyleEx-Objekt von ShapeEx. Die Farben der Füllung können davon abhängen. |

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Kachel android.graphics.Bitmap.