---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objek tak berubah yang berisi properti rig cahaya yang efektif.
type: docs
url: /id/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Objek tak berubah yang berisi properti rig cahaya yang efektif.

--------------------

Antarmuka ini digunakan sebagai bagian dari [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDirection()](#getDirection--) | Arah cahaya. |
| [getLightType()](#getLightType--) | Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. |
| [getRotation()](#getRotation--) | Rotasi didefinisikan melalui penggunaan koordinat latitude, koordinat longitude, dan revolusi tentang poros sebagaimana koordinat latitude dan longitude. |

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

Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. Rig cahaya mewakili sekumpulan cahaya yang diarahkan dengan cara tertentu relatif terhadap adegan 3D. Hanya-baca [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Mengembalikan:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotasi didefinisikan melalui penggunaan koordinat latitude, koordinat longitude, dan revolusi tentang poros sebagaimana koordinat latitude dan longitude. Elemen pertama dalam array yang dikembalikan - latitude, kedua - longitude, ketiga - revolusi.

**Mengembalikan:**
float[] - Koordinat rotasi sebagai float[]