---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /de/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Unveränderliches Objekt, das effektive Musterfüllungseigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) und [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Gibt den Musterstil zurück. |
| [getForeColor()](#getForeColor--) | Gibt die Vordergrund-Musterfarbe zurück. |
| [getBackColor()](#getBackColor--) | Gibt die Hintergrund-Musterfarbe zurück. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Gibt den Musterstil zurück. Nur lesbar [PatternStyle](../../com.aspose.slides/patternstyle).

**Rückgabe:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

Gibt die Vordergrund-Musterfarbe zurück. Nur lesbar java.lang.Integer.

**Rückgabe:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

Gibt die Hintergrund-Musterfarbe zurück. Nur lesbar java.lang.Integer.

**Rückgabe:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

Erstellt ein Kachelbild für die Musterfüllung mit angegebenen Farben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| background | java.lang.Integer | Das Hintergrund-java.lang.Integer für das Muster. |
| foreground | java.lang.Integer | Das Vordergrund-java.lang.Integer für das Muster. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Kachel [IImage](../../com.aspose.slides/iimage).