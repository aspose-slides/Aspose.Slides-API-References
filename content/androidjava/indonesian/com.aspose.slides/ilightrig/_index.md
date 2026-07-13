---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
type: docs
url: /id/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Mewakili LightRig.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDirection()](#getDirection--) | Arah cahaya. |
| [setDirection(int value)](#setDirection-int-) | Arah cahaya. |
| [getLightType()](#getLightType--) | Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. |
| [setLightType(int value)](#setLightType-int-) | Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotasi didefinisikan melalui penggunaan koordinat latitude, koordinat longitude, dan revolusi sekitar sumbu sebagai koordinat latitude dan longitude. |
| [getRotation()](#getRotation--) | Rotasi didefinisikan melalui penggunaan koordinat latitude, koordinat longitude, dan revolusi sekitar sumbu sebagai koordinat latitude dan longitude. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Arah cahaya. Baca/tulis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Mengembalikan:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Arah cahaya. Baca/tulis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. Light rig mewakili sekelompok cahaya yang berorientasi dengan cara tertentu relatif terhadap adegan 3D. Baca/tulis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Mengembalikan:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. Light rig mewakili sekelompok cahaya yang berorientasi dengan cara tertentu relatif terhadap adegan 3D. Baca/tulis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Rotasi didefinisikan melalui penggunaan koordinat latitude, koordinat longitude, dan revolusi sekitar sumbu sebagai koordinat latitude dan longitude.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| latitude | float | Koordinat latitude float |
| longitude | float | Koordinat longitude float |
| revolution | float | Koordinat revolusi float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotasi didefinisikan melalui penggunaan koordinat latitude, koordinat longitude, dan revolusi sekitar sumbu sebagai koordinat latitude dan longitude. elemen pertama dalam array hasil - latitude, kedua - longitude, ketiga - revolusi.

**Mengembalikan:**
float[] - Koordinat rotasi sebagai float[]