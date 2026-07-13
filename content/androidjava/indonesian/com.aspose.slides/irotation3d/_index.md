---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili rotasi 3D dari sebuah diagram.
type: docs
url: /id/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Mewakili rotasi 3D dari sebuah diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRotationX()](#getRotationX--) | Mengembalikan atau mengatur derajat rotasi di sekitar sumbu X, yaitu |
| [setRotationX(byte value)](#setRotationX-byte-) | Mengembalikan atau mengatur derajat rotasi di sekitar sumbu X, yaitu |
| [getRotationY()](#getRotationY--) | Mengembalikan atau mengatur derajat rotasi di sekitar sumbu Y, yaitu |
| [setRotationY(int value)](#setRotationY-int-) | Mengembalikan atau mengatur derajat rotasi di sekitar sumbu Y, yaitu |
| [getPerspective()](#getPerspective--) | Mengembalikan atau mengatur nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Mengembalikan atau mengatur nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Menentukan apakah sumbu diagram berada pada sudut tegak lurus, bukan digambar dalam perspektif. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Menentukan apakah sumbu diagram berada pada sudut tegak lurus, bukan digambar dalam perspektif. |
| [getDepthPercents()](#getDepthPercents--) | Mengembalikan atau mengatur kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Mengembalikan atau mengatur kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). |
| [getHeightPercents()](#getHeightPercents--) | Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Mengembalikan atau mengatur derajat rotasi di sekitar sumbu X, yaitu dalam arah Y untuk diagram 3D (antara -90 dan 90 derajat). Properti ini cocok dengan item 21.2.2.157 rotX (X Rotation) dalam ECMA-376 dan dengan opsi "Y Rotation" di PowerPoint 2007+. Baca/tulis byte.

**Mengembalikan:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Mengembalikan atau mengatur derajat rotasi di sekitar sumbu X, yaitu dalam arah Y untuk diagram 3D (antara -90 dan 90 derajat). Properti ini cocok dengan item 21.2.157 rotX (X Rotation) dalam ECMA-376 dan dengan opsi "Y Rotation" di PowerPoint 2007+. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Mengembalikan atau mengatur derajat rotasi di sekitar sumbu Y, yaitu dalam arah X untuk diagram 3D (antara 0 dan 360 derajat). Properti ini cocok dengan item 21.2.2.158 rotY (Y Rotation) dalam ECMA-376 dan dengan opsi "X Rotation" di PowerPoint 2007+. Baca/tulis int.

**Mengembalikan:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Mengembalikan atau mengatur derajat rotasi di sekitar sumbu Y, yaitu dalam arah X untuk diagram 3D (antara 0 dan 360 derajat). Properti ini cocok dengan item 21.2.2.158 rotY (Y Rotation) dalam ECMA-376 dan dengan opsi "X Rotation" di PowerPoint 2007+. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Mengembalikan atau mengatur nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 100). Diabaikan jika nilai properti RightAngleAxes bernilai true. Baca/tulis byte.

**Mengembalikan:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Mengembalikan atau mengatur nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 100). Diabaikan jika nilai properti RightAngleAxes bernilai true. Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Menentukan apakah sumbu diagram berada pada sudut tegak lurus, bukan digambar dalam perspektif. Dengan kata lain, ini menentukan apakah sudut sumbu diagram independen dari rotasi atau elevasi diagram. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Menentukan apakah sumbu diagram berada pada sudut tegak lurus, bukan digambar dalam perspektif. Dengan kata lain, ini menentukan apakah sudut sumbu diagram independen dari rotasi atau elevasi diagram. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Mengembalikan atau mengatur kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). Baca/tulis int.

**Mengembalikan:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Mengembalikan atau mengatur kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). Baca/tulis int.

**Mengembalikan:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |