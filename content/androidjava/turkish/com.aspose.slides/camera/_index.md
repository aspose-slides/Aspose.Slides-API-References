---
title: Camera
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Kamerayı temsil eder.
type: docs
url: /tr/com.aspose.slides/camera/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Kamerayı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Kamera türü. |
| [setCameraType(int value)](#setCameraType-int-) | Kamera türü. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Kamera FOV (0-180 derece, görüş alanı). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Kamera FOV (0-180 derece, görüş alanı). |
| [getZoom()](#getZoom--) | Kamera zoom (yüzde olarak pozitif değer). |
| [setZoom(float value)](#setZoom-float-) | Kamera zoom (yüzde olarak pozitif değer). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında bir devrim kullanılarak tanımlanır. |
| [getRotation()](#getRotation--) | Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında bir devrim kullanılarak tanımlanır. |
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


Kamera türü. Okunur/yazılır [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Döndürür:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```


Kamera türü. Okunur/yazılır [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```


Kamera FOV (0-180 derece, görüş alanı). Okunur/yazılır float.

**Döndürür:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```


Kamera FOV (0-180 derece, görüş alanı). Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```


Kamera zoom (yüzde olarak pozitif değer). Okunur/yazılır float.

**Döndürür:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```


Kamera zoom (yüzde olarak pozitif değer). Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında bir devrim kullanılarak tanımlanır. Eğer koordinat değerlerinden herhangi biri Float.NaN ise, tüm dönüş tanımsızdır.

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


Bir dönüş, enlem koordinatı, boylam koordinatı ve eksen etrafında bir devrim kullanılarak tanımlanır. Döndürme dizisinin ilk öğesi - enlem, ikincisi - boylam, üçüncüsü - devrim. Dönüş tanımlı değilse null döndürür.

**Döndürür:**
float[]