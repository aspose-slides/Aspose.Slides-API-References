---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Stelt een aanpassingswaarde voor een geometrische vorm voor.
type: docs
url: /nl/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Stelt een aanpassingswaarde voor een geometrische vorm voor. Deze waarden beïnvloeden de vorm van de vorm.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRawValue()](#getRawValue--) | Geeft de aanpassingswaarde "as is" terug of stelt deze in. |
| [setRawValue(long value)](#setRawValue-long-) | Geeft de aanpassingswaarde "as is" terug of stelt deze in. |
| [getAngleValue()](#getAngleValue--) | Geeft de waarde terug of stelt deze in, waarbij deze wordt geïnterpreteerd als een hoek in graden. |
| [setAngleValue(float value)](#setAngleValue-float-) | Geeft de waarde terug of stelt deze in, waarbij deze wordt geïnterpreteerd als een hoek in graden. |
| [getName()](#getName--) | Geeft de naam van deze aanpassingswaarde terug. |
| [getType()](#getType--) | Geeft het type van de vormaanpassing terug. |

### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Geeft de aanpassingswaarde "as is" terug of stelt deze in. Lezen/schrijven long.

**Retour:**
long

### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Geeft de aanpassingswaarde "as is" terug of stelt deze in. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Geeft de waarde terug of stelt deze in, waarbij deze wordt geïnterpreteerd als een hoek in graden. Lezen/schrijven float.

**Retour:**
float

### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Geeft de waarde terug of stelt deze in, waarbij deze wordt geïnterpreteerd als een hoek in graden. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

Geeft een naam van deze aanpassingswaarde terug. Alleen-lezen String.

**Retour:**
java.lang.String

### getType() {#getType--}
```
public abstract int getType()
```

Geeft het type van de vormaanpassing terug. Alleen-lezen [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Retour:**
int