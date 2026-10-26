---
title: IReflectionEffectiveData
second_title: Aspose.Slides için Java API Referansı
description: Bir Yansıma etkisini temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ireflectioneffectivedata/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

Yansıma efekti temsil eden değişmez nesne.
## Methods

| Yöntem | Açıklama |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Başlangıç alfa değerinin (yüzde) alfa gradyan rampa boyunca başlangıç konumunu belirtir. |
| [getEndPosAlpha()](#getEndPosAlpha--) | Bitiş alfa değerinin (yüzde) alfa gradyan rampa boyunca bitiş konumunu belirtir. |
| [getFadeDirection()](#getFadeDirection--) | Yansımanın kaydırma yönünü belirtir. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Başlangıç yansıma opaklığı. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Bitiş yansıma opaklığı. |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklaştırma yarıçapı. |
| [getDirection()](#getDirection--) | Yansımanın yönü. |
| [getDistance()](#getDistance--) | Yansıma mesafesi. |
| [getRectangleAlign()](#getRectangleAlign--) | Dikdörtgen hizalaması. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Yatay çarpıklık açısını belirtir. |
| [getSkewVertical()](#getSkewVertical--) | Dikey çarpıklık açısını belirtir. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Şekil döndürülürse yansımanın şekille birlikte dönüp dönmeyeceğini belirtir. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Yatay ölçeklendirme katsayısını belirtir, negatif ölçekleme ters çevrilmeye neden olur. |
| [getScaleVertical()](#getScaleVertical--) | Dikey ölçeklendirme katsayısını belirtir, negatif ölçekleme ters çevrilmeye neden olur. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Başlangıç alfa değerinin (yüzde) alfa gradyan rampa boyunca başlangıç konumunu belirtir. Salt okunur float.

**Döndürür:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Bitiş alfa değerinin (yüzde) alfa gradyan rampa boyunca bitiş konumunu belirtir. Salt okunur float.

**Döndürür:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Yansımanın kaydırma yönünü belirtir. (açı). Salt okunur float.

**Döndürür:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

Başlangıç yansıma opaklığı. (yüzde). Salt okunur float.

**Döndürür:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

Bitiş yansıma opaklığı. (yüzde). Salt okunur float.

**Döndürür:**
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Bulanıklaştırma yarıçapı. Salt okunur double.

**Döndürür:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Yansımanın yönü. Salt okunur float.

**Döndürür:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Yansıma mesafesi. Salt okunur double.

**Döndürür:**
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Dikdörtgen hizalaması. Salt okunur [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Döndürür:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Yatay çarpıklık açısını belirtir. Salt okunur double.

**Döndürür:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Dikey çarpıklık açısını belirtir. Salt okunur double.

**Döndürür:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Şekil döndürülürse yansımanın şekille birlikte dönüp dönmeyeceğini belirtir. Salt okunur boolean.

**Döndürür:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Yatay ölçeklendirme katsayısını belirtir, negatif ölçekleme ters çevrilmeye neden olur. (yüzde) Salt okunur double.

**Döndürür:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Dikey ölçeklendirme katsayısını belirtir, negatif ölçekleme ters çevrilmeye neden olur. (yüzde) Salt okunur double.

**Döndürür:**
double