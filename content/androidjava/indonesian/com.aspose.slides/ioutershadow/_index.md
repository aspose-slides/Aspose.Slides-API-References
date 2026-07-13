---
title: IOuterShadow
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili efek Outer Shadow.
type: docs
url: /id/com.aspose.slides/ioutershadow/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Mewakili efek Outer Shadow.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Radius blur, dalam poin. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Radius blur, dalam poin. |
| [getDirection()](#getDirection--) | Arah bayangan, dalam derajat. |
| [setDirection(float value)](#setDirection-float-) | Arah bayangan, dalam derajat. |
| [getDistance()](#getDistance--) | Jarak bayangan dari objek, dalam poin. |
| [setDistance(double value)](#setDistance-double-) | Jarak bayangan dari objek, dalam poin. |
| [getShadowColor()](#getShadowColor--) | Warna bayangan. |
| [getRectangleAlign()](#getRectangleAlign--) | Perataan persegi panjang. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Perataan persegi panjang. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Sudut kemiringan horizontal, dalam derajat. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Sudut kemiringan horizontal, dalam derajat. |
| [getSkewVertical()](#getSkewVertical--) | Sudut kemiringan vertikal, dalam derajat. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Sudut kemiringan vertikal, dalam derajat. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Menunjukkan apakah bayangan berputar bersama bentuk. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Menunjukkan apakah bayangan berputar bersama bentuk. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Faktor skala horizontal, dalam persentase ukuran asli. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Faktor skala horizontal, dalam persentase ukuran asli. |
| [getScaleVertical()](#getScaleVertical--) | Faktor skala vertikal, dalam persentase ukuran asli. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Faktor skala vertikal, dalam persentase ukuran asli. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Radius blur, dalam poin. Nilai default - 0 pt. Baca/tulis double.

**Mengembalikan:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Radius blur, dalam poin. Nilai default - 0 pt. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Arah bayangan, dalam derajat. Nilai default - 0 � (left-to-right). Baca/tulis float.

**Mengembalikan:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Arah bayangan, dalam derajat. Nilai default - 0 � (left-to-right). Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Jarak bayangan dari objek, dalam poin. Nilai default - 0 pt. Baca/tulis double.

**Mengembalikan:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Jarak bayangan dari objek, dalam poin. Nilai default - 0 pt. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Warna bayangan. Nilai default - hitam otomatis (tergantung tema). Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Perataan persegi panjang. Nilai default - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Baca/tulis [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Mengembalikan:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Perataan persegi panjang. Nilai default - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Baca/tulis [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Sudut kemiringan horizontal, dalam derajat. Nilai default - 0 �. Baca/tulis double.

**Mengembalikan:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Sudut kemiringan horizontal, dalam derajat. Nilai default - 0 �. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Sudut kemiringan vertikal, dalam derajat. Nilai default - 0 �. Baca/tulis double.

**Mengembalikan:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Sudut kemiringan vertikal, dalam derajat. Nilai default - 0 �. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Menunjukkan apakah bayangan berputar bersama bentuk. Nilai default - true. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Menunjukkan apakah bayangan berputar bersama bentuk. Nilai default - true. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Faktor skala horizontal, dalam persentase ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default - 100 %. Baca/tulis double.

**Mengembalikan:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Faktor skala horizontal, dalam persentase ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default - 100 %. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Faktor skala vertikal, dalam persentase ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default - 100 %. Baca/tulis double.

**Mengembalikan:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Faktor skala vertikal, dalam persentase ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default - 100 %. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |