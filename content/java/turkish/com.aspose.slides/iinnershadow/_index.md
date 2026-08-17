---
title: IInnerShadow
second_title: Aspose.Slides for Java API Referansı
description: İç gölge efektini temsil eder.
type: docs
url: /tr/com.aspose.slides/iinnershadow/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

İç gölge efektini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklaştırma yarıçapı. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bulanıklaştırma yarıçapı. |
| [getDirection()](#getDirection--) | Gölgenin yönü. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü. |
| [getDistance()](#getDistance--) | Gölgenin mesafesi. |
| [setDistance(double value)](#setDistance-double-) | Gölgenin mesafesi. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Bulanıklaştırma yarıçapı. Okunur/yazılır double.

**Döndürür:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Bulanıklaştırma yarıçapı. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Gölgenin yönü. Okunur/yazılır float.

**Döndürür:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Gölgenin yönü. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Gölgenin mesafesi. Okunur/yazılır double.

**Döndürür:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Gölgenin mesafesi. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Gölgenin rengi. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)