---
title: IReflection
second_title: Aspose.Slides için Java API Referansı
description: Bir yansıma efektini temsil eder.
type: docs
url: /tr/com.aspose.slides/ireflection/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

Bir yansıma efektini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Başlangıç alfa değerinin (yüzde) başlangıç konumunu (alfa gradyan rampa boyunca) belirtir. |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | Başlangıç alfa değerinin (yüzde) başlangıç konumunu (alfa gradyan rampa boyunca) belirtir. |
| [getEndPosAlpha()](#getEndPosAlpha--) | Bitiş alfa değerinin (yüzde) bitiş konumunu (alfa gradyan rampa boyunca) belirtir. |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | Bitiş alfa değerinin (yüzde) bitiş konumunu (alfa gradyan rampa boyunca) belirtir. |
| [getFadeDirection()](#getFadeDirection--) | Yansımanın kaydırma yönünü belirtir. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Yansımanın kaydırma yönünü belirtir. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Başlangıç yansıma opaklığını (yüzde) belirtir. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | Başlangıç yansıma opaklığını (yüzde) belirtir. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Bitiş yansıma opaklığını (yüzde) belirtir. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | Bitiş yansıma opaklığını (yüzde) belirtir. |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklık yarıçapını belirtir. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bulanıklık yarıçapını belirtir. |
| [getDirection()](#getDirection--) | Yansımanın yönünü belirtir. |
| [setDirection(float value)](#setDirection-float-) | Yansımanın yönünü belirtir. |
| [getDistance()](#getDistance--) | Yansımanın mesafesini belirtir. |
| [setDistance(double value)](#setDistance-double-) | Yansımanın mesafesini belirtir. |
| [getRectangleAlign()](#getRectangleAlign--) | Dikdörtgen hizalamasını belirtir. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Dikdörtgen hizalamasını belirtir. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Yatay eğim açısını belirtir. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Yatay eğim açısını belirtir. |
| [getSkewVertical()](#getSkewVertical--) | Dikey eğim açısını belirtir. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Dikey eğim açısını belirtir. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Şekil döndürülürse yansımanın şekille birlikte döndürülüp döndürülmeyeceğini belirtir. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Şekil döndürülürse yansımanın şekille birlikte döndürülüp döndürülmeyeceğini belirtir. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Yatay ölçekleme faktörünü belirtir, negatif ölçekleme bir döndürmeye (ters çevirme) neden olur. (yüzde) |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Yatay ölçekleme faktörünü belirtir, negatif ölçekleme bir döndürmeye (ters çevirme) neden olur. (yüzde) |
| [getScaleVertical()](#getScaleVertical--) | Dikey ölçekleme faktörünü belirtir, negatif ölçekleme bir döndürmeye (ters çevirme) neden olur. (yüzde) |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Dikey ölçekleme faktörünü belirtir, negatif ölçekleme bir döndürmeye (ters çevirme) neden olur. (yüzde) |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Başlangıç alfa değerinin (yüzde) başlangıç konumunu (alfa gradyan rampa boyunca) belirtir. Okunur/yazılır float.

**Döndürür:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

Başlangıç alfa değerinin (yüzde) başlangıç konumunu (alfa gradyan rampa boyunca) belirtir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Bitiş alfa değerinin (yüzde) bitiş konumunu (alfa gradyan rampa boyunca) belirtir. Okunur/yazılır float.

**Döndürür:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

Bitiş alfa değerinin (yüzde) bitiş konumunu (alfa gradyan rampa boyunca) belirtir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Yansımanın kaydırma yönünü belirtir. (açı). Okunur/yazılır float.

**Döndürür:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

Yansımanın kaydırma yönünü belirtir. (açı). Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

Başlangıç yansıma opaklığını (yüzde) belirtir. Okunur/yazılır float.

**Döndürür:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

Başlangıç yansıma opaklığını (yüzde) belirtir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

Bitiş yansıma opaklığını (yüzde) belirtir. Okunur/yazılır float.

**Döndürür:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

Bitiş yansıma opaklığını (yüzde) belirtir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Bulanıklık yarıçapını belirtir. Okunur/yazılır double.

**Döndürür:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Bulanıklık yarıçapını belirtir. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Yansımanın yönünü belirtir. Okunur/yazılır float.

**Döndürür:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Yansımanın yönünü belirtir. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Yansımanın mesafesini belirtir. Okunur/yazılır double.

**Döndürür:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Yansımanın mesafesini belirtir. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Dikdörtgen hizalamasını belirtir. Okunur/yazılır [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Döndürür:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Dikdörtgen hizalamasını belirtir. Okunur/yazılır [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Yatay eğim açısını belirtir. Okunur/yazılır double.

**Döndürür:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Yatay eğim açısını belirtir. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Dikey eğim açısını belirtir. Okunur/yazılır double.

**Döndürür:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Dikey eğim açısını belirtir. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Şekil döndürülürse yansımanın şekille birlikte döndürülüp döndürülmeyeceğini belirtir. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Şekil döndürülürse yansımanın şekille birlikte döndürülüp döndürülmeyeceğini belirtir. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Yatay ölçekleme faktörünü belirtir, negatif ölçekleme bir döndürmeye (ters çevirme) neden olur. (yüzde) Okunur/yazılır double.

**Döndürür:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Yatay ölçekleme faktörünü belirtir, negatif ölçekleme bir döndürmeye (ters çevirme) neden olur. (yüzde) Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Dikey ölçekleme faktörünü belirtir, negatif ölçekleme bir döndürmeye (ters çevirme) neden olur. (yüzde) Okunur/yazılır double.

**Döndürür:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Dikey ölçekleme faktörünü belirtir, negatif ölçekleme bir döndürmeye (ters çevirme) neden olur. (yüzde) Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |