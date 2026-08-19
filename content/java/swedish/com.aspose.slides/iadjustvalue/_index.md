---
title: IAdjustValue
second_title: Aspose.Slides för Java API-referens
description: Representerar ett justeringsvärde för en geometrisk form.
type: docs
url: /sv/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Representerar ett justeringsvärde för en geometrisk form. Dessa värden påverkar formens utseende.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRawValue()](#getRawValue--) | Returnerar eller anger justeringsvärdet "så som det är". |
| [setRawValue(long value)](#setRawValue-long-) | Returnerar eller anger justeringsvärdet "så som det är". |
| [getAngleValue()](#getAngleValue--) | Returnerar eller anger värde, tolkat som en vinkel i grader. |
| [setAngleValue(float value)](#setAngleValue-float-) | Returnerar eller anger värde, tolkat som en vinkel i grader. |
| [getName()](#getName--) | Returnerar ett namn på detta justeringsvärde. |
| [getType()](#getType--) | Returnerar typen av formjusteringen. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Returnerar eller anger justeringsvärde "så som det är". Läs/skriv long.

**Returnerar:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Returnerar eller anger justeringsvärde "så som det är". Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Returnerar eller anger värde, tolkat som en vinkel i grader. Läs/skriv float.

**Returnerar:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Returnerar eller anger värde, tolkat som en vinkel i grader. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Returnerar ett namn på detta justeringsvärde. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Returnerar typen av formjusteringen. Skrivskyddad [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Returnerar:**
int