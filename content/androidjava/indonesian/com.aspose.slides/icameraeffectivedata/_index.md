---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /id/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Objek tak dapat diubah yang berisi properti kamera yang efektif.

--------------------

Antarmuka ini digunakan sebagai bagian dari [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metode

| Method | Deskripsi |
| --- | --- |
| [getCameraType()](#getCameraType--) | Tipe kamera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 derajat, bidang pandang). |
| [getZoom()](#getZoom--) | Zoom kamera (nilai positif dalam persentase). |
| [getRotation()](#getRotation--) | Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Tipe kamera. Hanya-baca [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Mengembalikan:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180 derajat, bidang pandang). Hanya-baca float.

**Mengembalikan:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Zoom kamera (nilai positif dalam persentase). Hanya-baca float.

**Mengembalikan:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. elemen pertama dalam array yang dikembalikan - lintang, kedua - bujur, ketiga - revolusi. Mengembalikan null jika tidak ada rotasi yang didefinisikan.

**Mengembalikan:**
float[] - Array nilai rotasi sebagai float[].