---
title: ShapeElement
second_title: Aspose.Slides untuk Java Referensi API
description: Mewakili bagian dari shape dengan properti outline dan fill yang sama.
type: docs
url: /id/com.aspose.slides/shapeelement/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Mewakili bagian dari shape dengan properti outline dan fill yang sama.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParentShape()](#getParentShape--) | Mengembalikan Shape_PPT untuk elemen yang dibuat. |
| [getPathPoints()](#getPathPoints--) | Mendapatkan array titik yang mendefinisikan geometri jalur elemen. |
| [getPathTypes()](#getPathTypes--) | Mendapatkan array nilai byte yang menentukan tipe setiap titik dalam jalur elemen. |
| [getFillSource()](#getFillSource--) | Mengembalikan informasi tentang cara mengisi sebuah elemen. |
| [getStrokeSource()](#getStrokeSource--) | Mengembalikan informasi tentang cara stroke sebuah elemen. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Mengembalikan Shape_PPT untuk elemen yang dibuat. Hanya-baca [Shape](../../com.aspose.slides/shape).

**Mengembalikan:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


Mendapatkan array titik yang mendefinisikan geometri jalur elemen.

**Mengembalikan:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


Mendapatkan array nilai byte yang menentukan tipe setiap titik dalam jalur elemen.

**0** Menunjukkan bahwa titik tersebut adalah awal sebuah gambar.

**1** Menunjukkan bahwa titik tersebut adalah salah satu dari dua ujung garis.

**3** Menunjukkan bahwa titik tersebut adalah ujung atau titik kontrol dari spline Bezier kubik.

**7** Menyembunyikan semua bit kecuali tiga bit urutan rendah, yang menunjukkan tipe titik.

**16** Menentukan bahwa segmen yang bersangkutan berupa garis putus-putus.

**32** Menentukan bahwa titik tersebut adalah penanda.

**128** Menentukan bahwa titik tersebut adalah titik terakhir dalam subpath tertutup (gambar).

**129** Menunjukkan titik data yang sekaligus merupakan ujung segmen garis dan titik terakhir dari subpath tertutup.

**Mengembalikan:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


Mengembalikan informasi tentang cara mengisi sebuah elemen. Hanya-baca [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Mengembalikan:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


Mengembalikan informasi tentang cara stroke sebuah elemen. Hanya-baca [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Mengembalikan:**
byte