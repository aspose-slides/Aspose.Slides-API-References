---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /tr/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Bir geometri şeklinin ayarlama değerini temsil eder. Bu değerler şeklin formunu etkiler.
## Metotlar

| Metot | Açıklama |
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

Ayarlama değerini olduğu gibi alır veya ayarlar. Okunur/yazılır long.

**Döndürür:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Ayarlama değerini olduğu gibi alır veya ayarlar. Okunur/yazılır long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Değeri derece cinsinden açı olarak yorumlayarak alır veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Değeri derece cinsinden açı olarak yorumlayarak alır veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Bu ayarlama değerinin adını alır. Yalnızca-okunur String.

**Döndürür:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Şekil ayarlamasının türünü alır. Yalnızca-okunur [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Döndürür:**
int