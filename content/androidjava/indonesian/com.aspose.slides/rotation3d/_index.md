---
title: Rotation3D
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili rotasi 3D dari diagram.
type: docs
url: /id/com.aspose.slides/rotation3d/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Mewakili rotasi 3D dari diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRotationX()](#getRotationX--) | Mengembalikan atau mengatur derajat rotasi di sekitar sumbu X, yaitu |
| [setRotationX(byte value)](#setRotationX-byte-) | Mengembalikan atau mengatur derajat rotasi di sekitar sumbu X, yaitu |
| [getRotationY()](#getRotationY--) | Mengembalikan atau mengatur derajat rotasi di sekitar sumbu Y, yaitu |
| [setRotationY(int value)](#setRotationY-int-) | Mengembalikan atau mengatur derajat rotasi di sekitar sumbu Y, yaitu |
| [getPerspective()](#getPerspective--) | Mengembalikan atau mengatur nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Mengembalikan atau mengatur nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Menentukan apakah sumbu diagram berada pada sudut kanan, bukan digambar dalam perspektif. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Menentukan apakah sumbu diagram berada pada sudut kanan, bukan digambar dalam perspektif. |
| [getDepthPercents()](#getDepthPercents--) | Mengembalikan atau mengatur kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Mengembalikan atau mengatur kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). |
| [getHeightPercents()](#getHeightPercents--) | Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Mengembalikan atau mengatur derajat rotasi di sekitar sumbu X, yaitu pada arah Y untuk diagram 3D (antara -90 dan 90 derajat). Properti ini cocok dengan item 21.2.2.157 rotX (X Rotation) dalam ECMA-376 dan dengan opsi "Y Rotation" di PowerPoint 2007+. Baca/tulis byte.

**Mengembalikan:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Mengembalikan atau mengatur derajat rotasi di sekitar sumbu X, yaitu pada arah Y untuk diagram 3D (antara -90 dan 90 derajat). Properti ini cocok dengan item 21.2.2.157 rotX (X Rotation) dalam ECMA-376 dan dengan opsi "Y Rotation" di PowerPoint 2007+. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Mengembalikan atau mengatur derajat rotasi di sekitar sumbu Y, yaitu pada arah X untuk diagram 3D (antara 0 dan 360 derajat). Properti ini cocok dengan item 21.2.2.158 rotY (Y Rotation) dalam ECMA-376 dan dengan opsi "X Rotation" di PowerPoint 2007+. Baca/tulis int.

**Mengembalikan:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Mengembalikan atau mengatur derajat rotasi di sekitar sumbu Y, yaitu pada arah X untuk diagram 3D (antara 0 dan 360 derajat). Properti ini cocok dengan item 21.2.158 rotY (Y Rotation) dalam ECMA-376 dan dengan opsi "X Rotation" di PowerPoint 2007+. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Mengembalikan atau mengatur nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 240). Diabaikan jika nilai properti RightAngleAxes true. Baca/tulis byte.

**Mengembalikan:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Mengembalikan atau mengatur nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 240). Diabaikan jika nilai properti RightAngleAxes true. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Menentukan apakah sumbu diagram berada pada sudut kanan, bukan digambar dalam perspektif. Dengan kata lain, ini menentukan apakah sudut sumbu diagram independen dari rotasi atau elevasi diagram. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Menentukan apakah sumbu diagram berada pada sudut kanan, bukan digambar dalam perspektif. Dengan kata lain, ini menentukan apakah sudut sumbu diagram independen dari rotasi atau elevasi diagram. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Mengembalikan atau mengatur kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). Baca/tulis int.

**Mengembalikan:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Mengembalikan atau mengatur kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). Baca/tulis int.

**Mengembalikan:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject