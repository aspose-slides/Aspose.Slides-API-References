---
title: IAdjustValue
second_title: Aspose.Slides für Android via Java API Referenz
description: Stellt einen Anpassungswert für geometrische Formen dar.
type: docs
url: /de/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Stellt einen Anpassungswert einer geometrischen Form dar. Diese Werte beeinflussen die Form der Form.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRawValue()](#getRawValue--) | Liefert oder setzt den Anpassungswert "wie er ist". |
| [setRawValue(long value)](#setRawValue-long-) | Liefert oder setzt den Anpassungswert "wie er ist". |
| [getAngleValue()](#getAngleValue--) | Liefert oder setzt den Wert, interpretiert ihn als Winkel in Grad. |
| [setAngleValue(float value)](#setAngleValue-float-) | Liefert oder setzt den Wert, interpretiert ihn als Winkel in Grad. |
| [getName()](#getName--) | Liefert einen Namen dieses Anpassungswerts. |
| [getType()](#getType--) | Liefert den Typ der Formanpassung. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Liefert oder setzt den Anpassungswert "wie er ist". Lesen/Schreiben long.

**Rückgabe:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Liefert oder setzt den Anpassungswert "wie er ist". Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Liefert oder setzt den Wert, interpretiert ihn als Winkel in Grad. Lesen/Schreiben float.

**Rückgabe:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Liefert oder setzt den Wert, interpretiert ihn als Winkel in Grad. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Liefert einen Namen dieses Anpassungswerts. Nur-Lesen String.

**Rückgabe:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Liefert den Typ der Formanpassung. Nur-Lesen [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Rückgabe:**
int