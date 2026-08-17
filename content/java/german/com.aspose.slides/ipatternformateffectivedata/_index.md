---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides für Java API Reference
description: Unveränderliches Objekt, das effektive Musterfüll-Eigenschaften enthält.
type: docs
url: /de/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Unveränderliches Objekt, das effektive Musterfüll-Eigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) und [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Gibt den Musterstil zurück. |
| [getForeColor()](#getForeColor--) | Gibt die Vordergrund-Musterfarbe zurück. |
| [getBackColor()](#getBackColor--) | Gibt die Hintergrund-Musterfarbe zurück. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Erstellt ein Kachel-Bild für die Musterfüllung mit angegebenen Farben. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Gibt den Musterstil zurück. Nur lesbar [PatternStyle](../../com.aspose.slides/patternstyle).

**Rückgabe:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Gibt die Vordergrund-Musterfarbe zurück. Nur lesbar java.awt.Color.

**Rückgabe:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Gibt die Hintergrund-Musterfarbe zurück. Nur lesbar java.awt.Color.

**Rückgabe:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


Erstellt ein Kachel-Bild für die Musterfüllung mit angegebenen Farben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| background | java.awt.Color | Die Hintergrund-java.awt.Color für das Muster. |
| foreground | java.awt.Color | Die Vordergrund-java.awt.Color für das Muster. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Kachel [IImage](../../com.aspose.slides/iimage).