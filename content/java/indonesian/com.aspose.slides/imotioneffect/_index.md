---
title: IMotionEffect
second_title: Referensi API Aspose.Slides untuk Java
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
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Menentukan koordinat x/y untuk memulai animasi (dalam persen). |
| [getTo()](#getTo--) | Menentukan lokasi target untuk efek gerakan animasi (dalam persen). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Menentukan lokasi target untuk efek gerakan animasi (dalam persen). |
| [getBy()](#getBy--) | Menjelaskan nilai offset relatif untuk animasi (dalam persen). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Menjelaskan nilai offset relatif untuk animasi (dalam persen). |
| [getRotationCenter()](#getRotationCenter--) | Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerakan sebesar X sudut. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerakan sebesar X sudut. |
| [getOrigin()](#getOrigin--) | Menentukan apa asal jalur gerakan relatif terhadap seperti tata letak slide, atau induk. |
| [setOrigin(int value)](#setOrigin-int-) | Menentukan apa asal jalur gerakan relatif terhadap seperti tata letak slide, atau induk. |
| [getPath()](#getPath--) | Menentukan primitif jalur yang diikuti oleh koordinat untuk gerakan animasi. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Menentukan primitif jalur yang diikuti oleh koordinat untuk gerakan animasi. |
| [getPathEditMode()](#getPathEditMode--) | Menentukan bagaimana jalur gerakan bergerak ketika bentuk dipindahkan. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Menentukan bagaimana jalur gerakan bergerak ketika bentuk dipindahkan. |
| [getAngle()](#getAngle--) | Menjelaskan sudut relatif jalur gerakan. |
| [setAngle(float value)](#setAngle-float-) | Menjelaskan sudut relatif jalur gerakan. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Menentukan koordinat x/y untuk memulai animasi (dalam persen). Baca/tulis java.awt.geom.Point2D.Float.

**Mengembalikan:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Menentukan koordinat x/y untuk memulai animasi (dalam persen). Baca/tulis java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Menentukan lokasi target untuk efek gerakan animasi (dalam persen). Baca/tulis java.awt.geom.Point2D.Float.

**Mengembalikan:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Menentukan lokasi target untuk efek gerakan animasi (dalam persen). Baca/tulis java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Menjelaskan nilai offset relatif untuk animasi (dalam persen). Baca/tulis java.awt.geom.Point2D.Float.

**Mengembalikan:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Menjelaskan nilai offset relatif untuk animasi (dalam persen). Baca/tulis java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerakan sebesar X sudut. Baca/tulis java.awt.geom.Point2D.Float.

**Mengembalikan:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Menjelaskan pusat rotasi yang digunakan untuk memutar jalur gerakan sebesar X sudut. Baca/tulis java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Menentukan apa asal jalur gerakan relatif terhadap seperti tata letak slide, atau induk. Baca/tulis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Mengembalikan:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Menentukan apa asal jalur gerakan relatif terhadap seperti tata letak slide, atau induk. Baca/tulis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Menentukan primitif jalur yang diikuti oleh koordinat untuk gerakan animasi. Baca/tulis [IMotionPath](../../com.aspose.slides/imotionpath).

**Mengembalikan:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Menentukan primitif jalur yang diikuti oleh koordinat untuk gerakan animasi. Baca/tulis [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Menentukan bagaimana jalur gerakan bergerak ketika bentuk dipindahkan. Baca/tulis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Mengembalikan:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Menentukan bagaimana jalur gerakan bergerak ketika bentuk dipindahkan. Baca/tulis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Menjelaskan sudut relatif jalur gerakan. Baca/tulis float.

**Mengembalikan:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Menjelaskan sudut relatif jalur gerakan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |