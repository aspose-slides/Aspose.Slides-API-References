---
title: LightRig
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili LightRig.
type: docs
url: /id/com.aspose.slides/lightrig/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Mewakili LightRig.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Arah cahaya. |
| [setDirection(int value)](#setDirection-int-) | Arah cahaya. |
| [getLightType()](#getLightType--) | Mewakili preset light right yang dapat diterapkan pada shape. |
| [setLightType(int value)](#setLightType-int-) | Mewakili preset light right yang dapat diterapkan pada shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi tentang sumbu sebagai koordinat lintang dan bujur. |
| [getRotation()](#getRotation--) | Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi tentang sumbu sebagai koordinat lintang dan bujur. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versi. Baca-saja long.

**Mengembalikan:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


Arah cahaya. Baca/tulis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Mengembalikan:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Arah cahaya. Baca/tulis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```


Mewakili preset light right yang dapat diterapkan pada shape. Light rig mewakili sekelompok cahaya yang diarahkan secara khusus relatif terhadap adegan 3D. Baca/tulis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Mengembalikan:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Mewakili preset light right yang dapat diterapkan pada shape. Light rig mewakili sekelompok cahaya yang diarahkan secara khusus relatif terhadap adegan 3D. Baca/tulis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi tentang sumbu sebagai koordinat lintang dan bujur. Jika nilai koordinat mana pun adalah Float.NaN, semua rotasi tidak terdefinisi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


Rotasi didefinisikan melalui penggunaan koordinat lintang, koordinat bujur, dan revolusi tentang sumbu sebagai koordinat lintang dan bujur. elemen pertama dalam array yang dikembalikan - latitude, elemen kedua - longitude, elemen ketiga - revolution. Mengembalikan null jika tidak ada rotasi yang didefinisikan.

**Mengembalikan:**
float[]