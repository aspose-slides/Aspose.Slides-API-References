---
title: IInnerShadow
second_title: Aspose.Slides for Android için Java API Referansı
description: İç gölge efekti temsil eder.
type: docs
url: /tr/com.aspose.slides/iinnershadow/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

İç gölge efekti temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklık yarıçapı. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bulanıklık yarıçapı. |
| [getDirection()](#getDirection--) | Gölgenin yönü. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü. |
| [getDistance()](#getDistance--) | Gölgenin mesafesi. |
| [setDistance(double value)](#setDistance-double-) | Gölgenin mesafesi. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Bulanıklık yarıçapı. Okunur/yazılabilir double.

**Döndürür:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Bulanıklık yarıçapı. Okunur/yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Gölgenin yönü. Okunur/yazılabilir float.

**Döndürür:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Gölgenin yönü. Okunur/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Gölgenin mesafesi. Okunur/yazılabilir double.

**Döndürür:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Gölgenin mesafesi. Okunur/yazılabilir double.

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