---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Etkili kamera özelliklerini içeren değişmez nesne.
type: docs
url: /tr/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Etkili kamera özelliklerini içeren değişmez nesne.

--------------------

Bu arabirim [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) parçası olarak kullanılmaktadır.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getCameraType()](#getCameraType--) | Kamera türü. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 derece, görüş alanı). |
| [getZoom()](#getZoom--) | Kamera yakınlaştırma (yüzde olarak pozitif değer). |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki dönüşle, enlem ve boylam koordinatları kullanılarak tanımlanır. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Kamera türü. Salt okunur [CameraPresetType](../../com.aspose.slides/camerapresettype).

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

Kamera yakınlaştırma (yüzde olarak pozitif değer). Salt okunur float.

**Döndürür:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafındaki dönüşle, enlem ve boylam koordinatları kullanılarak tanımlanır. Döndürme dizisinin ilk öğesi - enlem, ikinci - boylam, üçüncü - dönüş. Tanımlı dönüş yoksa null döner.

**Döndürür:**
float[] - Dönüş değerlerinin float[] dizisi.