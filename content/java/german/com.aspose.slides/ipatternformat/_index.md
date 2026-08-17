---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /de/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Repräsentiert ein Muster zum Füllen einer Form.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Gibt den Musterstil zurück oder legt ihn fest. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Gibt den Musterstil zurück oder legt ihn fest. |
| [getForeColor()](#getForeColor--) | Gibt die Vordergrundfarbe des Musters zurück. |
| [getBackColor()](#getBackColor--) | Gibt die Hintergrundfarbe des Musters zurück. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Erstellt ein Kachelbild für die Musterfüllung. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Gibt den Musterstil zurück oder legt ihn fest. Lese/Schreib [PatternStyle](../../com.aspose.slides/patternstyle).

**Rückgabe:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Gibt den Musterstil zurück oder legt ihn fest. Lese/Schreib [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Gibt die Vordergrundfarbe des Musters zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Gibt die Hintergrundfarbe des Musters zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| background | java.awt.Color | Die Hintergrund-java.awt.Color für das Muster. |
| foreground | java.awt.Color | Die Vordergrund-java.awt.Color für das Muster. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Erstellt ein Kachelbild für die Musterfüllung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleColor | java.awt.Color | Die Standard-java.awt.Color, definiert im StyleEx-Objekt von ShapeEx. Die Farben der Füllung können davon abhängen. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.