---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /tr/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Etkili kamera özelliklerini içeren değişmez nesne.

--------------------

This interface is used as a part of [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kamera tipi. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 derece, görüş alanı). |
| [getZoom()](#getZoom--) | Kamera yakınlaştırması (yüzde olarak pozitif değer). |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve enlem ve boylam koordinatları olarak eksen etrafında yapılan devrim kullanılarak tanımlanır. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Kamera tipi. Salt okunur [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Döndürür:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Kamera FOV (0-180 derece, görüş alanı). Salt okunur float.

**Döndürür:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Kamera yakınlaştırması (yüzde olarak pozitif değer). Salt okunur float.

**Döndürür:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Bir dönüş, enlem koordinatı, boylam koordinatı ve enlem ve boylam koordinatları olarak eksen etrafında yapılan devrim kullanılarak tanımlanır. dönüş dizisindeki ilk eleman - enlem, ikinci - boylam, üçüncü - devrim. Tanımlı dönüş yoksa null döndürür.

**Döndürür:**
float[] - Rotasyon değerlerinin float[] dizisi.