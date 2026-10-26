---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Referensi
description: Mewakili satu perintah pada jalur.
type: docs
url: /id/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Mewakili satu perintah pada jalur.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPoints()](#getPoints--) | Menentukan titik-titik perintah. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Menentukan titik-titik perintah. |
| [getCommandType()](#getCommandType--) | Menentukan jenis perintah. |
| [setCommandType(int value)](#setCommandType-int-) | Menentukan jenis perintah. |
| [isRelative()](#isRelative--) | Menentukan apakah koordinat perintah relatif atau tidak. |
| [setRelative(boolean value)](#setRelative-boolean-) | Menentukan apakah koordinat perintah relatif atau tidak. |
| [getPointsType()](#getPointsType--) | Menentukan jenis titik perintah Baca/tulis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Menentukan jenis titik perintah Baca/tulis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```


Menentukan titik-titik perintah. Baca/tulis android.graphics.PointF[].

**Mengembalikan:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```


Menentukan titik-titik perintah. Baca/tulis android.graphics.PointF[].

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```


Menentukan jenis perintah. Baca/tulis [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Mengembalikan:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```


Menentukan jenis perintah. Baca/tulis [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```


Menentukan apakah koordinat perintah relatif atau tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```


Menentukan apakah koordinat perintah relatif atau tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```


Menentukan jenis titik perintah Baca/tulis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Mengembalikan:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```


Menentukan jenis titik perintah Baca/tulis [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |