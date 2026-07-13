---
title: ShapeElement
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili bagian dari bentuk dengan properti outline dan isi yang sama.
type: docs
url: /id/com.aspose.slides/shapeelement/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Mewakili bagian dari bentuk dengan properti outline dan isi yang sama.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParentShape()](#getParentShape--) | Mengembalikan Shape_PPT untuk elemen yang dibuat. |
| [getPathPoints()](#getPathPoints--) | Mendapatkan array titik yang mendefinisikan geometri jalur elemen. |
| [getPathTypes()](#getPathTypes--) | Mendapatkan array nilai byte yang menentukan tipe tiap titik dalam jalur elemen. |
| [getFillSource()](#getFillSource--) | Mengembalikan informasi tentang cara mengisi elemen. |
| [getStrokeSource()](#getStrokeSource--) | Mengembalikan informasi tentang cara memberi garis pada elemen. |

### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Mengembalikan Shape_PPT untuk elemen yang dibuat. Hanya-baca [Shape](../../com.aspose.slides/shape).

**Mengembalikan:**
[Shape](../../com.aspose.slides/shape)

### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Mendapatkan array titik yang mendefinisikan geometri jalur elemen.

**Mengembalikan:**
android.graphics.PointF[]

### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Mendapatkan array nilai byte yang menentukan tipe tiap titik dalam jalur elemen.

**0** Menunjukkan bahwa titik tersebut adalah awal sebuah figur.  
**1** Menunjukkan bahwa titik tersebut adalah salah satu dari dua ujung sebuah garis.  
**3** Menunjukkan bahwa titik tersebut adalah ujung atau titik kontrol dari spline Bezier kubik.  
**7** Menyembunyikan semua bit kecuali tiga bit urutan rendah yang menunjukkan tipe titik.  
**16** Menentukan bahwa segmen yang bersesuaian bersifat garis putus-putus.  
**32** Menentukan bahwa titik tersebut adalah penanda.  
**128** Menentukan bahwa titik tersebut adalah titik terakhir dalam subpath tertutup (figur).  
**129** Menunjukkan titik data yang merupakan ujung segmen garis sekaligus titik terakhir dari subpath tertutup.  

**Mengembalikan:**
byte[]

### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Mengembalikan informasi tentang cara mengisi elemen. Hanya-baca [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Mengembalikan:**
byte

### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Mengembalikan informasi tentang cara memberi garis pada elemen. Hanya-baca [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Mengembalikan:**
byte