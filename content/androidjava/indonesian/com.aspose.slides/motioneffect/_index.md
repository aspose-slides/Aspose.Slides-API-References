---
title: MotionEffect
second_title: Referensi API Java untuk Aspose.Slides di Android
description: Mewakili perilaku efek gerakan dari efek.
type: docs
url: /id/com.aspose.slides/motioneffect/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Mewakili perilaku efek gerakan dari efek.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFrom()](#getFrom--) | Menentukan koordinat x/y untuk memulai animasi (dalam persen). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Menentukan koordinat x/y untuk memulai animasi (dalam persen). |
| [getTo()](#getTo--) | Menentukan lokasi target untuk efek gerakan animasi (dalam persen). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Menentukan lokasi target untuk efek gerakan animasi (dalam persen). |
| [getBy()](#getBy--) | Menjelaskan nilai offset relatif untuk animasi (dalam persen). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Menjelaskan nilai offset relatif untuk animasi (dalam persen). |
| [getRotationCenter()](#getRotationCenter--) | Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerakan sebesar sudut X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerakan sebesar sudut X. |
| [getOrigin()](#getOrigin--) | Menentukan apa asal jalur gerakan relatif terhadap seperti tata letak slide, atau induk. |
| [setOrigin(int value)](#setOrigin-int-) | Menentukan apa asal jalur gerakan relatif terhadap seperti tata letak slide, atau induk. |
| [getPath()](#getPath--) | Menentukan primitif jalur yang diikuti koordinat untuk gerakan animasi. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Menentukan primitif jalur yang diikuti koordinat untuk gerakan animasi. |
| [getPathEditMode()](#getPathEditMode--) | Menentukan bagaimana jalur gerakan bergerak ketika bentuk dipindahkan. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Menentukan bagaimana jalur gerakan bergerak ketika bentuk dipindahkan. |
| [getAngle()](#getAngle--) | Menjelaskan sudut relatif jalur gerakan. |
| [setAngle(float value)](#setAngle-float-) | Menjelaskan sudut relatif jalur gerakan. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final PointF getFrom()
```


Menentukan koordinat x/y untuk memulai animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```


Menentukan koordinat x/y untuk memulai animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```


Menentukan lokasi target untuk efek gerakan animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```


Menentukan lokasi target untuk efek gerakan animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```


Menjelaskan nilai offset relatif untuk animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```


Menjelaskan nilai offset relatif untuk animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```


Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerakan sebesar sudut X. Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```


Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerakan sebesar sudut X. Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


Menentukan apa asal jalur gerakan relatif terhadap seperti tata letak slide, atau induk. Baca/tulis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Mengembalikan:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


Menentukan apa asal jalur gerakan relatif terhadap seperti tata letak slide, atau induk. Baca/tulis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


Menentukan primitif jalur yang diikuti koordinat untuk gerakan animasi. Baca/tulis [IMotionPath](../../com.aspose.slides/imotionpath).

**Mengembalikan:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


Menentukan primitif jalur yang diikuti koordinat untuk gerakan animasi. Baca/tulis [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


Menentukan bagaimana jalur gerakan bergerak ketika bentuk dipindahkan. Baca/tulis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Mengembalikan:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


Menentukan bagaimana jalur gerakan bergerak ketika bentuk dipindahkan. Baca/tulis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


Menjelaskan sudut relatif jalur gerakan. Baca/tulis float.

**Mengembalikan:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


Menjelaskan sudut relatif jalur gerakan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |