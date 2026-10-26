---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /it/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Rappresenta il valore di regolazione di una forma geometrica. Questi valori influenzano la forma della figura.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRawValue()](#getRawValue--) | Returns or sets adjustment value "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Returns or sets adjustment value "as is". |
| [getAngleValue()](#getAngleValue--) | Returns or sets value, interpreting it as angle in degrees. |
| [setAngleValue(float value)](#setAngleValue-float-) | Returns or sets value, interpreting it as angle in degrees. |
| [getName()](#getName--) | Returns a name of this adjustment value. |
| [getType()](#getType--) | Returns the type of the shape adjustment. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Restituisce o imposta il valore di regolazione "as is". Lettura/scrittura long.

**Restituisce:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Restituisce o imposta il valore di regolazione "as is". Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Restituisce o imposta il valore, interpretandolo come angolo in gradi. Lettura/scrittura float.

**Restituisce:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Restituisce o imposta il valore, interpretandolo come angolo in gradi. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Restituisce un nome di questo valore di regolazione. Sola lettura String.

**Restituisce:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Restituisce il tipo di regolazione della forma. Sola lettura [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Restituisce:**
int