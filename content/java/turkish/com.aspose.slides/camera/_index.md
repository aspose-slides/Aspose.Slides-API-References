---
title: Camera
second_title: Aspose.Slides for Java API Referansı
description: Kamerayı temsil eder.
type: docs
url: /tr/com.aspose.slides/camera/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Kamerayı temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Kamera türü. |
| [setCameraType(int value)](#setCameraType-int-) | Kamera türü. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera görüş alanı (0-180 derece, field of View). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera görüş alanı (0-180 derece, field of View). |
| [getZoom()](#getZoom--) | Kamera yakınlaştırma (yüzde cinsinden pozitif değer). |
| [setZoom(float value)](#setZoom-float-) | Kamera yakınlaştırma (yüzde cinsinden pozitif değer). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur long.

**Döndürür:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Kamera türü. Okunabilir/yazılabilir [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Döndürür:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Kamera türü. Okunabilir/yazılabilir [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Kamera görüş alanı (0-180 derece, field of View). Okunabilir/yazılabilir float.

**Döndürür:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Kamera görüş alanı (0-180 derece, field of View). Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Kamera yakınlaştırma (yüzde cinsinden pozitif değer). Okunabilir/yazılabilir float.

**Döndürür:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Kamera yakınlaştırma (yüzde cinsinden pozitif değer). Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. Koordinat değerlerinden biri Float.NaN ise tüm dönüş tanımsızdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında enlem ve boylam koordinatları olarak bir devrim kullanılarak tanımlanır. Dönüş dizisinin ilk elemanı - enlem, ikincisi - boylam, üçüncüsü - devrim. Tanımlı bir dönüş yoksa null döndürür.

**Döndürür:**
float[]