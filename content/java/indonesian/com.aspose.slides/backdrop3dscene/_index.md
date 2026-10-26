---
title: Backdrop3DScene
second_title: Referensi API Aspose.Slides untuk Java
description: Mendefinisikan sebuah bidang di mana efek seperti cahaya bersinar dan bayangan diterapkan terkait dengan bentuk yang menerima efek tersebut.
type: docs
url: /id/com.aspose.slides/backdrop3dscene/
---
**Warisan:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Mendefinisikan sebuah bidang di mana efek, seperti cahaya bersinar dan bayangan, diterapkan terkait dengan bentuk yang menerima efek.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Mengembalikan atau mengatur vektor normal. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Mengembalikan atau mengatur vektor normal. |
| [getAnchorPoint()](#getAnchorPoint--) | Mengembalikan atau mengatur titik dalam ruang 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Mengembalikan atau mengatur titik dalam ruang 3D. |
| [getUpVector()](#getUpVector--) | Mengembalikan atau mengatur vektor yang merepresentasikan arah atas. |
| [setUpVector(float[] value)](#setUpVector-float---) | Mengembalikan atau mengatur vektor yang merepresentasikan arah atas. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Long hanya-baca.

**Mengembalikan:**  
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Mengembalikan atau mengatur vektor normal. Lebih tepatnya, atribut ini mendefinisikan sebuah vektor yang normal terhadap permukaan bidang latar. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Mengembalikan:**  
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Mengembalikan atau mengatur vektor normal. Lebih tepatnya, atribut ini mendefinisikan sebuah vektor yang normal terhadap permukaan bidang latar. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Mengembalikan atau mengatur titik dalam ruang 3D. Titik ini adalah titik di ruang yang menjadi jangkar bidang latar. Titik 3D direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Mengembalikan:**  
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Mengembalikan atau mengatur titik dalam ruang 3D. Titik ini adalah titik di ruang yang menjadi jangkar bidang latar. Titik 3D direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Mengembalikan atau mengatur vektor yang merepresentasikan arah atas. Lebih tepatnya, atribut ini mendefinisikan sebuah vektor yang merepresentasikan arah atas relatif terhadap permukaan bidang latar. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Mengembalikan:**  
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Mengembalikan atau mengatur vektor yang merepresentasikan arah atas. Lebih tepatnya, atribut ini mendefinisikan sebuah vektor yang merepresentasikan arah atas relatif terhadap permukaan bidang latar. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. Baca/tulis float[].

**Parameter:**  
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |