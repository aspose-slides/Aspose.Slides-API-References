---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje wartość dopasowania kształtu geometrycznego.
type: docs
url: /pl/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Reprezentuje wartość dopasowania kształtu geometrycznego. Wartości te wpływają na formę kształtu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRawValue()](#getRawValue--) | Zwraca lub ustawia wartość dopasowania "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Zwraca lub ustawia wartość dopasowania "as is". |
| [getAngleValue()](#getAngleValue--) | Zwraca lub ustawia wartość, interpretując ją jako kąt w stopniach. |
| [setAngleValue(float value)](#setAngleValue-float-) | Zwraca lub ustawia wartość, interpretując ją jako kąt w stopniach. |
| [getName()](#getName--) | Zwraca nazwę tej wartości dopasowania. |
| [getType()](#getType--) | Zwraca typ dopasowania kształtu. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Zwraca lub ustawia wartość dopasowania "as is". Odczyt/zapis long.

**Zwraca:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Zwraca lub ustawia wartość dopasowania "as is". Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Zwraca lub ustawia wartość, interpretując ją jako kąt w stopniach. Odczyt/zapis float.

**Zwraca:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Zwraca lub ustawia wartość, interpretując ją jako kąt w stopniach. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Zwraca nazwę tej wartości dopasowania. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Zwraca typ dopasowania kształtu. Tylko do odczytu [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Zwraca:**
int