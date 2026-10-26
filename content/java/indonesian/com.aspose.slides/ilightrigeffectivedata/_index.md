---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /id/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Objek tidak dapat diubah yang berisi properti rig cahaya yang efektif.

--------------------

Antarmuka ini digunakan sebagai bagian dari [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDirection()](#getDirection--) | Arah cahaya. |
| [getLightType()](#getLightType--) | Mewakili lampu preset kanan yang dapat diterapkan pada sebuah bentuk. |
| [getRotation()](#getRotation--) | Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Arah cahaya. Hanya-baca [LightingDirection](../../com.aspose.slides/lightingdirection).

**Mengembalikan:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Mewakili lampu preset kanan yang dapat diterapkan pada sebuah bentuk. Rig cahaya mewakili sekelompok lampu yang diposisikan dengan cara tertentu relatif terhadap adegan 3D. Hanya-baca [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Mengembalikan:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi sekitar sumbu sebagai koordinat lintang dan bujur. Elemen pertama dalam array hasil - lintang, kedua - bujur, ketiga - revolusi.

**Mengembalikan:**
float[] - Koordinat rotasi sebagai float[]