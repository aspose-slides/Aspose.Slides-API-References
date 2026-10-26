---
title: IAdjustValue
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett justeringsvärde för en geometrisk form.
type: docs
url: /sv/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Representerar ett justeringsvärde för en geometrisk form. Dessa värden påverkar formens form.
## Metoder

| Method | Description |
| --- | --- |
| [getRawValue()](#getRawValue--) | Returnerar eller anger justeringsvärde "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Returnerar eller anger justeringsvärde "as is". |
| [getAngleValue()](#getAngleValue--) | Returnerar eller anger värde, tolkad som vinkel i grader. |
| [setAngleValue(float value)](#setAngleValue-float-) | Returnerar eller anger värde, tolkad som vinkel i grader. |
| [getName()](#getName--) | Returnerar ett namn för detta justeringsvärde. |
| [getType()](#getType--) | Returnerar typen av formjusteringen. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Returnerar eller anger justeringsvärde "as is". Läs/skriv long.

**Returnerar:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Returnerar eller anger justeringsvärde "as is". Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Returnerar eller anger värde, tolkad som vinkel i grader. Läs/skriv float.

**Returnerar:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Returnerar eller anger värde, tolkad som vinkel i grader. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Returnerar ett namn för detta justeringsvärde. Endast läsning String.

**Returnerar:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Returnerar typen av formjusteringen. Endast läsning [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Returnerar:**
int