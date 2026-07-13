---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /nl/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Representeert een aanpassingswaarde van een geometrische vorm. Deze waarden beïnvloeden de vorm van de shape.
## Methoden

| Method | Description |
| --- | --- |
| [getRawValue()](#getRawValue--) | Retourneert of stelt de aanpassingswaarde “zoals het is” in. |
| [setRawValue(long value)](#setRawValue-long-) | Retourneert of stelt de aanpassingswaarde “zoals het is” in. |
| [getAngleValue()](#getAngleValue--) | Retourneert of stelt de waarde in, waarbij deze wordt geïnterpreteerd als een hoek in graden. |
| [setAngleValue(float value)](#setAngleValue-float-) | Retourneert of stelt de waarde in, waarbij deze wordt geïnterpreteerd als een hoek in graden. |
| [getName()](#getName--) | Retourneert de naam van deze aanpassingswaarde. |
| [getType()](#getType--) | Retourneert het type van de vormaanpassing. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Retourneert of stelt de aanpassingswaarde “zoals het is” in. Lezen/schrijven long.

**Returns:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Retourneert of stelt de aanpassingswaarde “zoals het is” in. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Retourneert of stelt de waarde in, waarbij deze wordt geïnterpreteerd als een hoek in graden. Lezen/schrijven float.

**Returns:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Retourneert of stelt de waarde in, waarbij deze wordt geïnterpreteerd als een hoek in graden. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Retourneert de naam van deze aanpassingswaarde. Alleen-lezen String.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Retourneert het type van de vormaanpassing. Alleen-lezen [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Returns:**
int