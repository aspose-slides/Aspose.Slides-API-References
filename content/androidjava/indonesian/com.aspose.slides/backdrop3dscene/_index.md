---
title: Backdrop3DScene
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mendefinisikan bidang di mana efek seperti cahaya bersinar dan bayangan diterapkan relatif terhadap bentuk yang menjadi targetnya.
type: docs
url: /id/com.aspose.slides/backdrop3dscene/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Mendefinisikan bidang di mana efek, seperti cahaya bersinar dan bayangan, diterapkan relatif terhadap bentuk yang menjadi targetnya.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Mengembalikan atau mengatur vektor normal. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Mengembalikan atau mengatur vektor normal. |
| [getAnchorPoint()](#getAnchorPoint--) | Mengembalikan atau mengatur titik dalam ruang 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Mengembalikan atau mengatur titik dalam ruang 3D. |
| [getUpVector()](#getUpVector--) | Mengembalikan atau mengatur vektor yang merepresentasikan ke atas. |
| [setUpVector(float[] value)](#setUpVector-float---) | Mengembalikan atau mengatur vektor yang merepresentasikan ke atas. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Mengembalikan atau mengatur vektor normal. Lebih tepatnya, atribut ini mendefinisikan vektor yang tegak lurus terhadap bidang latar belakang. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Mengembalikan:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Mengembalikan atau mengatur vektor normal. Lebih tepatnya, atribut ini mendefinisikan vektor yang tegak lurus terhadap bidang latar belakang. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Mengembalikan atau mengatur titik dalam ruang 3D. Titik ini adalah titik di ruang yang menjadi jangkar bagi bidang latar belakang. Titik 3D direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Mengembalikan:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Mengembalikan atau mengatur titik dalam ruang 3D. Titik ini adalah titik di ruang yang menjadi jangkar bagi bidang latar belakang. Titik 3D direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Mengembalikan atau mengatur vektor yang merepresentasikan ke atas. Lebih tepatnya, atribut ini mendefinisikan vektor yang merepresentasikan ke atas relatif terhadap bidang latar belakang. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Mengembalikan:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Mengembalikan atau mengatur vektor yang merepresentasikan ke atas. Lebih tepatnya, atribut ini mendefinisikan vektor yang merepresentasikan ke atas relatif terhadap bidang latar belakang. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |