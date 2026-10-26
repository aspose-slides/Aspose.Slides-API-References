---
title: IAdjustValue
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta il valore di regolazione di una forma geometrica.
type: docs
url: /it/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Rappresenta il valore di regolazione di una forma geometrica. Questi valori influenzano la forma della forma.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRawValue()](#getRawValue--) | Restituisce o imposta il valore di regolazione "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Restituisce o imposta il valore di regolazione "as is". |
| [getAngleValue()](#getAngleValue--) | Restituisce o imposta il valore, interpretandolo come angolo in gradi. |
| [setAngleValue(float value)](#setAngleValue-float-) | Restituisce o imposta il valore, interpretandolo come angolo in gradi. |
| [getName()](#getName--) | Restituisce il nome di questo valore di regolazione. |
| [getType()](#getType--) | Restituisce il tipo della regolazione della forma. |
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


Restituisce il nome di questo valore di regolazione. Solo lettura String.

**Restituisce:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Restituisce il tipo della regolazione della forma. Solo lettura [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Restituisce:**
int