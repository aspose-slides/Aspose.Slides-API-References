---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Stellt einen Anpassungswert für geometrische Formen dar.
type: docs
url: /de/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Stellt den Anpassungswert einer geometrischen Form dar. Diese Werte beeinflussen die Form der Form.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRawValue()](#getRawValue--) | Liefert oder setzt den Anpassungswert „as is“. |
| [setRawValue(long value)](#setRawValue-long-) | Liefert oder setzt den Anpassungswert „as is“. |
| [getAngleValue()](#getAngleValue--) | Liefert oder setzt den Wert, interpretiert als Winkel in Grad. |
| [setAngleValue(float value)](#setAngleValue-float-) | Liefert oder setzt den Wert, interpretiert als Winkel in Grad. |
| [getName()](#getName--) | Liefert einen Namen dieses Anpassungswertes. |
| [getType()](#getType--) | Liefert den Typ der Formanpassung. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Liefert oder setzt den Anpassungswert „as is“. Lesen/Schreiben long.

**Rückgabewert:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Liefert oder setzt den Anpassungswert „as is“. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Liefert oder setzt den Wert, interpretiert als Winkel in Grad. Lesen/Schreiben float.

**Rückgabewert:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Liefert oder setzt den Wert, interpretiert als Winkel in Grad. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

Liefert einen Namen dieses Anpassungswertes. Nur-lesen String.

**Rückgabewert:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Liefert den Typ der Formanpassung. Nur-lesen [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Rückgabewert:**
int