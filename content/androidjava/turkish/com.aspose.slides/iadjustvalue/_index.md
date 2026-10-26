---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Geometri şeklinin ayarlama değerini temsil eder. Bu değerler şeklin biçimini etkiler.
type: docs
url: /tr/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Geometri şeklinin ayarlama değerini temsil eder. Bu değerler şeklin biçimini etkiler.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRawValue()](#getRawValue--) | Değişiklik değerini olduğu gibi döndürür veya ayarlar. |
| [setRawValue(long value)](#setRawValue-long-) | Değişiklik değerini olduğu gibi döndürür veya ayarlar. |
| [getAngleValue()](#getAngleValue--) | Değeri derece cinsinden bir açı olarak yorumlayarak döndürür veya ayarlar. |
| [setAngleValue(float value)](#setAngleValue-float-) | Değeri derece cinsinden bir açı olarak yorumlayarak döndürür veya ayarlar. |
| [getName()](#getName--) | Bu ayarlama değerinin adını döndürür. |
| [getType()](#getType--) | Şekil ayarlamasının türünü döndürür. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Değişiklik değerini olduğu gibi döndürür veya ayarlar. Okunur/yazılır long.

**Döndürür:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Değişiklik değerini olduğu gibi döndürür veya ayarlar. Okunur/yazılır long.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Değeri derece cinsinden bir açı olarak yorumlayarak döndürür veya ayarlar. Okunur/yazılır float.

**Döndürür:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Değeri derece cinsinden bir açı olarak yorumlayarak döndürür veya ayarlar. Okunur/yazılır float.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

Bu ayarlama değerinin adını döndürür. Yalnızca okunur String.

**Döndürür:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Şekil ayarlamasının türünü döndürür. Yalnızca okunur [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Döndürür:**
int