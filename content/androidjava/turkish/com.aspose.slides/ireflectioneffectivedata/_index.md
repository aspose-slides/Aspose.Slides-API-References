---
title: IReflectionEffectiveData
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Yansıma etkisini temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ireflectioneffectivedata/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

Yansıma etkisini temsil eden değiştirilemez nesne.
## Metotlar

| Method | Description |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Başlangıç alfa değerinin (yüzdeler) alfa gradyan rampa boyunca başlangıç konumunu belirtir. |
| [getEndPosAlpha()](#getEndPosAlpha--) | Son alfa değerinin (yüzdeler) alfa gradyan rampa boyunca son konumunu belirtir. |
| [getFadeDirection()](#getFadeDirection--) | Yansımanın kaydırma yönünü belirtir. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Başlangıç yansıma opaklığı. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Son yansıma opaklığı. |
| [getBlurRadius()](#getBlurRadius--) | Bulanıklaştırma yarıçapı. |
| [getDirection()](#getDirection--) | Yansıma yönü. |
| [getDistance()](#getDistance--) | Yansıma mesafesi. |
| [getRectangleAlign()](#getRectangleAlign--) | Dikdörtgen hizalaması. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Yatay çarpıtma açısını belirtir. |
| [getSkewVertical()](#getSkewVertical--) | Dikey çarpıtma açısını belirtir. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Şekil döndürülmüşse yansımanın şekille birlikte dönüp dönmeyeceğini belirtir. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Yatay ölçekleme faktörünü belirtir, negatif ölçekleme dönmeyi (flip) sağlar. |
| [getScaleVertical()](#getScaleVertical--) | Dikey ölçekleme faktörünü belirtir, negatif ölçekleme dönmeyi (flip) sağlar. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Başlangıç alfa değerinin (yüzdeler) alfa gradyan rampa boyunca başlangıç konumunu belirtir. Salt okunur float.

**Döndürür:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Son alfa değerinin (yüzdeler) alfa gradyan rampa boyunca son konumunu belirtir. Salt okunur float.

**Döndürür:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Yansımanın kaydırma yönünü (açı) belirtir. Salt okunur float.

**Döndürür:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

Başlangıç yansıma opaklığı (yüzdeler). Salt okunur float.

**Döndürür:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

Son yansıma opaklığı (yüzdeler). Salt okunur float.

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

Yansıma yönü. Salt okunur float.

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

Yatay çarpıtma açısını belirtir. Salt okunur double.

**Döndürür:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Dikey çarpıtma açısını belirtir. Salt okunur double.

**Döndürür:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Şekil döndürülmüşse yansımanın şekille birlikte dönüp dönmeyeceğini belirtir. Salt okunur boolean.

**Döndürür:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Yatay ölçekleme faktörünü belirtir, negatif ölçekleme dönmeyi (flip) sağlar. (yüzdeler) Salt okunur double.

**Döndürür:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Dikey ölçekleme faktörünü belirtir, negatif ölçekleme dönmeyi (flip) sağlar. (yüzdeler) Salt okunur double.

**Döndürür:**
double