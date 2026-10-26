---
title: LightRig
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili LightRig.
type: docs
url: /id/com.aspose.slides/lightrig/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Mewakili LightRig.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Arah cahaya. |
| [setDirection(int value)](#setDirection-int-) | Arah cahaya. |
| [getLightType()](#getLightType--) | Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. |
| [setLightType(int value)](#setLightType-int-) | Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi tentang sumbu sebagaimana koordinat lintang dan bujur. |
| [getRotation()](#getRotation--) | Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi tentang sumbu sebagaimana koordinat lintang dan bujur. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Returns:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Arah cahaya. Baca/tulis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Arah cahaya. Baca/tulis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. Light rig mewakili sekumpulan cahaya yang diorientasikan secara khusus relatif terhadap adegan 3D. Baca/tulis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Mewakili preset cahaya kanan yang dapat diterapkan pada bentuk. Light rig mewakili sekumpulan cahaya yang diorientasikan secara khusus relatif terhadap adegan 3D. Baca/tulis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi tentang sumbu sebagaimana koordinat lintang dan bujur. Jika salah satu nilai koordinat adalah Float.NaN, semua rotasi tidak terdefinisi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi tentang sumbu sebagaimana koordinat lintang dan bujur. elemen pertama dalam array yang dikembalikan - lintang, kedua - bujur, ketiga - revolusi. Mengembalikan null jika tidak ada rotasi yang didefinisikan.

**Returns:**
float[]