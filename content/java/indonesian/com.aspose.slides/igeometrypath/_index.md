---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /id/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Mewakili jalur geometri GeometryShape
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPathData()](#getPathData--) | Mengembalikan jalur geometri GeometryShape sebagai array segmen jalur. |
| [removeAt(int index)](#removeAt-int-) | Menghapus segmen pada indeks yang ditentukan dari jalur geometri. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Menambahkan garis ke akhir jalur |
| [lineTo(float x, float y)](#lineTo-float-float-) | Menambahkan garis ke akhir jalur |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Menambahkan garis ke tempat yang ditentukan pada jalur |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Menambahkan garis ke tempat yang ditentukan pada jalur |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Menambahkan kurva Bezier kubik di akhir jalur |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Menambahkan kurva Bezier kubik di akhir jalur |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Menambahkan kurva Bezier kuadratik di akhir jalur |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Menambahkan kurva Bezier kuadratik di akhir jalur |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur |
| [closeFigure()](#closeFigure--) | Menutup figure saat ini dari jalur ini |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Menetapkan posisi titik berikutnya. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Menetapkan posisi titik berikutnya. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Menambahkan busur yang ditentukan ke jalur. |
| [getFillMode()](#getFillMode--) | Menetapkan mode isi |
| [setFillMode(byte value)](#setFillMode-byte-) | Menetapkan mode isi |
| [getStroke()](#getStroke--) | Menetapkan tampilan stroke |
| [setStroke(boolean value)](#setStroke-boolean-) | Menetapkan tampilan stroke |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


Mengembalikan jalur geometri GeometryShape sebagai array segmen jalur.

**Mengembalikan:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus segmen pada indeks yang ditentukan dari jalur geometri.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks jalur geometri yang harus dihapus. |
### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```


Menambahkan garis ke akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Titik akhir garis |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Menambahkan garis ke akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X titik akhir garis |
| y | float | Koordinat Y titik akhir garis |
### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```


Menambahkan garis ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Titik akhir |
| index | long | Indeks segmen dalam PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


Menambahkan garis ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X titik |
| y | float | Koordinat Y titik |
| index | long | Indeks segmen dalam PathData |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Menambahkan kurva Bezier kubik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Titik arah pertama |
| point2 | java.awt.geom.Point2D.Float | Titik arah kedua |
| point3 | java.awt.geom.Point2D.Float | Titik akhir |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Menambahkan kurva Bezier kubik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X titik arah pertama |
| y1 | float | Koordinat Y titik arah pertama |
| x2 | float | Koordinat X titik arah kedua |
| y2 | float | Koordinat Y titik arah kedua |
| x3 | float | Koordinat X titik akhir |
| y3 | float | Koordinat Y titik akhir |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Titik arah pertama |
| point2 | java.awt.geom.Point2D.Float | Titik arah kedua |
| point3 | java.awt.geom.Point2D.Float | Titik akhir |
| index | long | Indeks segmen dalam PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X titik arah pertama |
| y1 | float | Koordinat Y titik arah pertama |
| x2 | float | Koordinat X titik arah kedua |
| y2 | float | Koordinat Y titik arah kedua |
| x3 | float | Koordinat X titik akhir |
| y3 | float | Koordinat Y titik akhir |
| index | long | Indeks segmen dalam PathData |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Menambahkan kurva Bezier kuadratik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Titik arah |
| point2 | java.awt.geom.Point2D.Float | Titik akhir |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Menambahkan kurva Bezier kuadratik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X titik arah |
| y1 | float | Koordinat Y titik arah |
| x2 | float | Koordinat X titik akhir |
| y2 | float | Koordinat Y titik akhir |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Titik arah |
| point2 | java.awt.geom.Point2D.Float | Titik akhir |
| index | long | Indeks segmen dalam PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X titik arah |
| y1 | float | Koordinat Y titik arah |
| x2 | float | Koordinat X titik akhir |
| y2 | float | Koordinat Y titik akhir |
| index | long | Indeks segmen dalam PathData |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


Menutup figure saat ini dari jalur ini
### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```


Menetapkan posisi titik berikutnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Posisi titik |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Menetapkan posisi titik berikutnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X titik |
| y | float | Koordinat Y titik |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Menambahkan busur yang ditentukan ke jalur.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | float | Lebar persegi panjang |
| heigth | float | Tinggi persegi panjang |
| startAngle | float | Sudut awal. |
| sweepAngle | float | Sudut sweep/ |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Menetapkan mode isi

**Mengembalikan:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Menetapkan mode isi

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Menetapkan tampilan stroke

**Mengembalikan:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Menetapkan tampilan stroke

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |