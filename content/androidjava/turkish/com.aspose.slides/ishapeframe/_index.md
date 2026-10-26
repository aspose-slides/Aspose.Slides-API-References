---
title: IShapeFrame
second_title: Aspose.Slides Android için Java API Referansı
description: Şekil çerçevelerinin özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ishapeframe/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Şekil çerçevesinin özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getX()](#getX--) | Bir çerçevenin sol üst köşesinin X koordinatını döndürür. |
| [getY()](#getY--) | Bir çerçevenin sol üst köşesinin Y koordinatını döndürür. |
| [getWidth()](#getWidth--) | Bir çerçevenin genişliğini döndürür. |
| [getHeight()](#getHeight--) | Bir çerçevenin yüksekliğini döndürür. |
| [getRotation()](#getRotation--) | Bir çerçevenin z ekseni etrafında döndürüldüğü derece sayısını döndürür. |
| [getCenterX()](#getCenterX--) | Bir çerçevenin merkezinin X koordinatını döndürür. |
| [getCenterY()](#getCenterY--) | Bir çerçevenin merkezinin Y koordinatını döndürür. |
| [getFlipH()](#getFlipH--) | Bir çerçevenin yatay olarak çevrilip çevrilmediğini belirler. |
| [getFlipV()](#getFlipV--) | Bir çerçevenin dikey olarak çevrilip çevrilmediğini belirler. |
| [getRectangle()](#getRectangle--) | Bir çerçevenin koordinatlarını döndürür. |
### getX() {#getX--}
```
public abstract float getX()
```


Bir çerçevenin sol üst köşesinin X koordinatını döndürür. Salt okunur float.

**Döndürür:**
float
### getY() {#getY--}
```
public abstract float getY()
```


Bir çerçevenin sol üst köşesinin Y koordinatını döndürür. Salt okunur float.

**Döndürür:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Bir çerçevenin genişliğini döndürür. Salt okunur float.

**Döndürür:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Bir çerçevenin yüksekliğini döndürür. Salt okunur float.

**Döndürür:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Bir çerçevenin z ekseni etrafında döndürüldüğü derece sayısını döndürür. Pozitif bir değer saat yönünde döndürmeyi; negatif bir değer saat yönünün tersine döndürmeyi gösterir. Salt okunur float.

**Döndürür:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


Bir çerçevenin merkezinin X koordinatını döndürür. Salt okunur float.

**Döndürür:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


Bir çerçevenin merkezinin Y koordinatını döndürür. Salt okunur float.

**Döndürür:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


Bir çerçevenin yatay olarak çevrilip çevrilmediğini belirler. Salt okunur [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


Bir çerçevenin dikey olarak çevrilip çevrilmediğini belirler. Salt okunur [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```


Bir çerçevenin koordinatlarını döndürür. Salt okunur android.graphics.RectF.

**Döndürür:**
android.graphics.RectF