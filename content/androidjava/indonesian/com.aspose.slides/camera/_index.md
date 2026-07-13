---
title: Camera
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili Kamera.
type: docs
url: /id/com.aspose.slides/camera/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Mewakili Kamera.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Tipe kamera. |
| [setCameraType(int value)](#setCameraType-int-) | Tipe kamera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV Kamera (0-180 deg, field of View). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV Kamera (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Zoom kamera (nilai positif dalam persentase). |
| [setZoom(float value)](#setZoom-float-) | Zoom kamera (nilai positif dalam persentase). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotasi didefinisikan dengan menggunakan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. |
| [getRotation()](#getRotation--) | Rotasi didefinisikan dengan menggunakan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Tipe kamera. Baca/tulis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Mengembalikan:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Tipe kamera. Baca/tulis [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

FOV Kamera (0-180 deg, field of View). Baca/tulis float.

**Mengembalikan:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

FOV Kamera (0-180 deg, field of View). Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

Zoom kamera (nilai positif dalam persentase). Baca/tulis float.

**Mengembalikan:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Zoom kamera (nilai positif dalam persentase). Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Rotasi didefinisikan dengan menggunakan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. Jika nilai koordinat mana pun adalah Float.NaN, semua rotasi tidak terdefinisi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Rotasi didefinisikan dengan menggunakan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. elemen pertama dalam array yang dikembalikan - lintang, kedua - bujur, ketiga - revolusi. Mengembalikan null jika tidak ada rotasi yang didefinisikan.

**Mengembalikan:**
float[]