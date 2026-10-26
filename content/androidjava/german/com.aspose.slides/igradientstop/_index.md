---
title: IGradientStop
second_title: Aspose.Slides für Android via Java API Referenz
description: Stellt ein Farbverlaufformat dar.
type: docs
url: /de/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Stellt ein Farbverlaufformat dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPosition()](#getPosition--) | Gibt die Position (0..1) eines Verlaufsstopp zurück oder legt sie fest. |
| [setPosition(float value)](#setPosition-float-) | Gibt die Position (0..1) eines Verlaufsstopp zurück oder legt sie fest. |
| [getColor()](#getColor--) | Gibt die Farbe eines Verlaufsstopp zurück. |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Gibt die Position (0..1) eines Verlaufsstopp zurück oder legt sie fest. Lese-/Schreib float.

**Rückgabe:**
float

### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Gibt die Position (0..1) eines Verlaufsstopp zurück oder legt sie fest. Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Gibt die Farbe eines Verlaufsstopp zurück. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)