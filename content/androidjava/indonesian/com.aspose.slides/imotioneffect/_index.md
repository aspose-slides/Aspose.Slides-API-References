---
title: IMotionEffect
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili perilaku efek gerakan dari efek.
type: docs
url: /id/com.aspose.slides/imotioneffect/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Mewakili perilaku efek gerakan dari efek.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFrom()](#getFrom--) | Menentukan koordinat x/y untuk memulai animasi (dalam persen). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Menentukan koordinat x/y untuk memulai animasi (dalam persen). |
| [getTo()](#getTo--) | Menentukan lokasi target untuk efek gerakan animasi (dalam persen). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Menentukan lokasi target untuk efek gerakan animasi (dalam persen). |
| [getBy()](#getBy--) | Menjelaskan nilai offset relatif untuk animasi (dalam persen). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Menjelaskan nilai offset relatif untuk animasi (dalam persen). |
| [getRotationCenter()](#getRotationCenter--) | Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerak dengan sudut X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerak dengan sudut X. |
| [getOrigin()](#getOrigin--) | Menentukan apa asal jalur gerak relatif terhadap, seperti tata letak slide, atau induknya. |
| [setOrigin(int value)](#setOrigin-int-) | Menentukan apa asal jalur gerak relatif terhadap, seperti tata letak slide, atau induknya. |
| [getPath()](#getPath--) | Menentukan primitif jalur diikuti oleh koordinat untuk gerakan animasi. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Menentukan primitif jalur diikuti oleh koordinat untuk gerakan animasi. |
| [getPathEditMode()](#getPathEditMode--) | Menentukan bagaimana jalur gerak bergerak ketika bentuk dipindahkan. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Menentukan bagaimana jalur gerak bergerak ketika bentuk dipindahkan. |
| [getAngle()](#getAngle--) | Menjelaskan sudut relatif jalur gerak. |
| [setAngle(float value)](#setAngle-float-) | Menjelaskan sudut relatif jalur gerak. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Menentukan koordinat x/y untuk memulai animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Menentukan koordinat x/y untuk memulai animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Menentukan lokasi target untuk efek gerakan animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Menentukan lokasi target untuk efek gerakan animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Menjelaskan nilai offset relatif untuk animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Menjelaskan nilai offset relatif untuk animasi (dalam persen). Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerak dengan sudut X. Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerak dengan sudut X. Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Menentukan apa asal jalur gerak relatif terhadap, seperti tata letak slide, atau induknya. Baca/tulis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Mengembalikan:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Menentukan apa asal jalur gerak relatif terhadap, seperti tata letak slide, atau induknya. Baca/tulis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Menentukan primitif jalur diikuti oleh koordinat untuk gerakan animasi. Baca/tulis [IMotionPath](../../com.aspose.slides/imotionpath).

**Mengembalikan:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Menentukan primitif jalur diikuti oleh koordinat untuk gerakan animasi. Baca/tulis [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Menentukan bagaimana jalur gerak bergerak ketika bentuk dipindahkan. Baca/tulis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Mengembalikan:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Menentukan bagaimana jalur gerak bergerak ketika bentuk dipindahkan. Baca/tulis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Menjelaskan sudut relatif jalur gerak. Baca/tulis float.

**Mengembalikan:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Menjelaskan sudut relatif jalur gerak. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |