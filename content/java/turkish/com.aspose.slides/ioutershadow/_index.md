---
title: IOuterShadow
second_title: Aspose.Slides Java API Referansı
description: Dış Gölge etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/ioutershadow/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Dış Gölge etkisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklaştırma yarıçapı, nokta cinsinden. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Bulanıklaştırma yarıçapı, nokta cinsinden. |
| [getDirection()](#getDirection--) | Gölgenin yönü, derece cinsinden. |
| [setDirection(float value)](#setDirection-float-) | Gölgenin yönü, derece cinsinden. |
| [getDistance()](#getDistance--) | Gölgenin nesneden uzaklığı, nokta cinsinden. |
| [setDistance(double value)](#setDistance-double-) | Gölgenin nesneden uzaklığı, nokta cinsinden. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
| [getRectangleAlign()](#getRectangleAlign--) | Dikdörtgen hizalaması. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Dikdörtgen hizalaması. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Yatay eğim açısı, derece cinsinden. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Yatay eğim açısı, derece cinsinden. |
| [getSkewVertical()](#getSkewVertical--) | Dikey eğim açısı, derece cinsinden. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Dikey eğim açısı, derece cinsinden. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Gölgenin şekille birlikte döndürülüp döndürülmediğini gösterir. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Gölgenin şekille birlikte döndürülüp döndürülmediğini gösterir. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Yatay ölçekleme faktörü, özgün boyutun yüzde cinsinden. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Yatay ölçekleme faktörü, özgün boyutun yüzde cinsinden. |
| [getScaleVertical()](#getScaleVertical--) | Dikey ölçekleme faktörü, özgün boyutun yüzde cinsinden. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Dikey ölçekleme faktörü, özgün boyutun yüzde cinsinden. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Bulanıklaştırma yarıçapı, nokta cinsinden. Varsayılan değer - 0 pt. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Bulanıklaştırma yarıçapı, nokta cinsinden. Varsayılan değer - 0 pt. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Gölgenin yönü, derece cinsinden. Varsayılan değer - 0 � (soldan sağa). Okunabilir/Yazılabilir float.

**Döndürür:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Gölgenin yönü, derece cinsinden. Varsayılan değer - 0 � (soldan sağa). Okunabilir/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Gölgenin nesneden uzaklığı, nokta cinsinden. Varsayılan değer - 0 pt. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Gölgenin nesneden uzaklığı, nokta cinsinden. Varsayılan değer - 0 pt. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Gölgenin rengi. Varsayılan değer - otomatik siyah (tema bağımlı). Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Dikdörtgen hizalaması. Varsayılan değer - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Okunabilir/Yazılabilir [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Döndürür:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Dikdörtgen hizalaması. Varsayılan değer - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Okunabilir/Yazılabilir [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Yatay eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Yatay eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Dikey eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Dikey eğim açısı, derece cinsinden. Varsayılan değer - 0 �. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Gölgenin şekille birlikte döndürülüp döndürülmediğini gösterir. Varsayılan değer - true. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Gölgenin şekille birlikte döndürülüp döndürülmediğini gösterir. Varsayılan değer - true. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Yatay ölçekleme faktörü, özgün boyutun yüzde cinsinden. Negatif ölçekleme bir ters çevirme oluşturur. Varsayılan değer - %100. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Yatay ölçekleme faktörü, özgün boyutun yüzde cinsinden. Negatif ölçekleme bir ters çevirme oluşturur. Varsayılan değer - %100. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Dikey ölçekleme faktörü, özgün boyutun yüzde cinsinden. Negatif ölçekleme bir ters çevirme oluşturur. Varsayılan değer - %100. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Dikey ölçekleme faktörü, özgün boyutun yüzde cinsinden. Negatif ölçekleme bir ters çevirme oluşturur. Varsayılan değer - %100. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |