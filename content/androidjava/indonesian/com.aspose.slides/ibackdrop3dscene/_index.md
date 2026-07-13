---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Mendefinisikan bidang di mana efek seperti cahaya bersinar dan bayangan diterapkan relatif terhadap bentuk yang diterapkan.
type: docs
url: /id/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Mendefinisikan bidang di mana efek, seperti cahaya bersinar dan bayangan, diterapkan relatif terhadap bentuk yang diterapkan pada.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Mengembalikan atau mengatur vektor normal. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Mengembalikan atau mengatur vektor normal. |
| [getAnchorPoint()](#getAnchorPoint--) | Mengembalikan atau mengatur titik dalam ruang 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Mengembalikan atau mengatur titik dalam ruang 3D. |
| [getUpVector()](#getUpVector--) | Mengembalikan atau mengatur vektor yang mewakili arah atas. |
| [setUpVector(float[] value)](#setUpVector-float---) | Mengembalikan atau mengatur vektor yang mewakili arah atas. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Mengembalikan atau mengatur vektor normal. Lebih tepatnya, atribut ini mendefinisikan vektor yang tegak lurus terhadap permukaan bidang backdrop. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. **Baca/tulis** float[].

**Mengembalikan:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Mengembalikan atau mengatur vektor normal. Lebih tepatnya, atribut ini mendefinisikan vektor yang tegak lurus terhadap permukaan bidang backdrop. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. **Baca/tulis** float[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Mengembalikan atau mengatur titik dalam ruang 3D. Titik ini adalah titik dalam ruang yang menjadi jangkar bidang backdrop. Titik 3D direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. **Baca/tulis** float[].

**Mengembalikan:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Mengembalikan atau mengatur titik dalam ruang 3D. Titik ini adalah titik dalam ruang yang menjadi jangkar bidang backdrop. Titik 3D direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. **Baca/tulis** float[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Mengembalikan atau mengatur vektor yang mewakili arah atas. Lebih tepatnya, atribut ini mendefinisikan vektor yang mewakili arah atas relatif terhadap permukaan bidang backdrop. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. **Baca/tulis** float[].

**Mengembalikan:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Mengembalikan atau mengatur vektor yang mewakili arah atas. Lebih tepatnya, atribut ini mendefinisikan vektor yang mewakili arah atas relatif terhadap permukaan bidang backdrop. Vektor direpresentasikan oleh array berisi 3 nilai float yang menentukan koordinat X, Y, dan Z. **Baca/tulis** float[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float[] |  |