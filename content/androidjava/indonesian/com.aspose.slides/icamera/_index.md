---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili Kamera.
type: docs
url: /id/com.aspose.slides/icamera/
---```
public interface ICamera
```

Mewakili Kamera.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipe kamera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Tipe kamera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV Kamera (0-180 derajat, bidang pandang) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV Kamera (0-180 derajat, bidang pandang) Read/write float. |
| [getZoom()](#getZoom--) | Zoom kamera (nilai positif dalam persentase) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | Zoom kamera (nilai positif dalam persentase) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. |
| [getRotation()](#getRotation--) | Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Tipe kamera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Mengembalikan:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Tipe kamera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


FOV Kamera (0-180 derajat, bidang pandang) Read/write float.

**Mengembalikan:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


FOV Kamera (0-180 derajat, bidang pandang) Read/write float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Zoom kamera (nilai positif dalam persentase) Read/write float.

**Mengembalikan:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Zoom kamera (nilai positif dalam persentase) Read/write float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. Jika nilai koordinat mana pun adalah Float.NaN, semua rotasi tidak terdefinisi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| latitude | float | Nilai lintang float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. elemen pertama dalam array yang dikembalikan - lintang, kedua - bujur, ketiga - revolusi. Mengembalikan null jika tidak ada rotasi yang didefinisikan.

**Mengembalikan:**
float[] - Array nilai rotasi sebagai float[].

