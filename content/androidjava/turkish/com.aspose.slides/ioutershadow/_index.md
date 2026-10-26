---
title: IOuterShadow
second_title: Aspose.Slides for Android via Java API Referansı
description: Dış Gölge etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/ioutershadow/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Dış Gölge etkisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklık yarıçapı, nokta cinsinden. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bulanıklık yarıçapı, nokta cinsinden. |
| [getDirection()](#getDirection--) | Gölgenin yönü, derece cinsinden. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü, derece cinsinden. |
| [getDistance()](#getDistance--) | Gölgenin nesneden uzaklığı, nokta cinsinden. |
| [setDistance(double value)](#setDistance-double-) | Gölgenin nesneden uzaklığı, nokta cinsinden. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
| [getRectangleAlign()](#getRectangleAlign--) | Dikdörtgen hizalaması. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Dikdörtgen hizalaması. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Yatay eğik açı, derece cinsinden. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Yatay eğik açı, derece cinsinden. |
| [getSkewVertical()](#getSkewVertical--) | Dikey eğik açı, derece cinsinden. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Dikey eğik açı, derece cinsinden. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Yatay ölçekleme faktörü, özgün boyutun yüzde olarak. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Yatay ölçekleme faktörü, özgün boyutun yüzde olarak. |
| [getScaleVertical()](#getScaleVertical--) | Dikey ölçekleme faktörü, özgün boyutun yüzde olarak. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Dikey ölçekleme faktörü, özgün boyutun yüzde olarak. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Bulanıklık yarıçapı, nokta cinsinden. Varsayılan değer - 0 pt. Okunur/yazılır double.

**Döndürür:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Bulanıklık yarıçapı, nokta cinsinden. Varsayılan değer - 0 pt. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Gölgenin yönü, derece cinsinden. Varsayılan değer - 0 � (soldan sağa). Okunur/yazılır float.

**Döndürür:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Gölgenin yönü, derece cinsinden. Varsayılan değer - 0 � (soldan sağa). Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Gölgenin nesneden uzaklığı, nokta cinsinden. Varsayılan değer - 0 pt. Okunur/yazılır double.

**Döndürür:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Gölgenin nesneden uzaklığı, nokta cinsinden. Varsayılan değer - 0 pt. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Gölgenin rengi. Varsayılan değer - otomatik siyah (tema bağımlı). Yalnızca okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Dikdörtgen hizalaması. Varsayılan değer - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Okunur/yazılır [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Döndürür:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Dikdörtgen hizalaması. Varsayılan değer - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Okunur/yazılır [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Yatay eğik açı, derece cinsinden. Varsayılan değer - 0 �. Okunur/yazılır double.

**Döndürür:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Yatay eğik açı, derece cinsinden. Varsayılan değer - 0 �. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Dikey eğik açı, derece cinsinden. Varsayılan değer - 0 �. Okunur/yazılır double.

**Döndürür:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Dikey eğik açı, derece cinsinden. Varsayılan değer - 0 �. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. Varsayılan değer - true. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. Varsayılan değer - true. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Yatay ölçekleme faktörü, özgün boyutun yüzde olarak. Negatif ölçekleme bir ters çevirme oluşturur. Varsayılan değer - %100. Okunur/yazılır double.

**Döndürür:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Yatay ölçekleme faktörü, özgün boyutun yüzde olarak. Negatif ölçekleme bir ters çevirme oluşturur. Varsayılan değer - %100. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Dikey ölçekleme faktörü, özgün boyutun yüzde olarak. Negatif ölçekleme bir ters çevirme oluşturur. Varsayılan değer - %100. Okunur/yazılır double.

**Döndürür:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Dikey ölçekleme faktörü, özgün boyutun yüzde olarak. Negatif ölçekleme bir ters çevirme oluşturur. Varsayılan değer - %100. Okunur/yazılır double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |