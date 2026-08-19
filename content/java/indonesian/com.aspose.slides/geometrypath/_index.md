---
title: GeometryPath
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili jalur geometri dari GeometryShape
type: docs
url: /id/com.aspose.slides/geometrypath/
---
**Pewarisan:**  
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)  
```
public final class GeometryPath implements IGeometryPath
```

Mewakili jalur geometri dari GeometryShape
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Membuat instance GeometryPath |
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
| [closeFigure()](#closeFigure--) | Menutup gambar saat ini dari jalur ini |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Mengatur posisi titik berikutnya. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Mengatur posisi titik berikutnya. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Menambahkan busur yang ditentukan ke jalur. |
| [getFillMode()](#getFillMode--) | Mengatur mode isi |
| [setFillMode(byte value)](#setFillMode-byte-) | Mengatur mode isi |
| [getStroke()](#getStroke--) | Mengatur tampilan stroke |
| [setStroke(boolean value)](#setStroke-boolean-) | Mengatur tampilan stroke |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Membuat instance GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Mengembalikan jalur geometri GeometryShape sebagai array segmen jalur.

**Mengembalikan:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus segmen pada indeks yang ditentukan dari jalur geometri.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks jalur geometri yang harus dihapus. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

Menambahkan garis ke akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Titik akhir garis |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Menambahkan garis ke akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari titik akhir garis |
| y | float | Koordinat Y dari titik akhir garis |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

Menambahkan garis ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Titik akhir |
| index | long | Indeks segmen dalam PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Menambahkan garis ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari titik |
| y | float | Koordinat Y dari titik |
| index | long | Indeks segmen dalam PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
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
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Menambahkan kurva Bezier kubik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X dari titik arah pertama |
| y1 | float | Koordinat Y dari titik arah pertama |
| x2 | float | Koordinat X dari titik arah kedua |
| y2 | float | Koordinat Y dari titik arah kedua |
| x3 | float | Koordinat X dari titik akhir |
| y3 | float | Koordinat Y dari titik akhir |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
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
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X dari titik arah pertama |
| y1 | float | Koordinat Y dari titik arah pertama |
| x2 | float | Koordinat X dari titik arah kedua |
| y2 | float | Koordinat Y dari titik arah kedua |
| x3 | float | Koordinat X dari titik akhir |
| y3 | float | Koordinat Y dari titik akhir |
| index | long | Indeks segmen dalam PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Menambahkan kurva Bezier kuadratik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Titik arah |
| point2 | java.awt.geom.Point2D.Float | Titik akhir |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Menambahkan kurva Bezier kuadratik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X dari titik arah |
| y1 | float | Koordinat Y dari titik arah |
| x2 | float | Koordinat X dari titik akhir |
| y2 | float | Koordinat Y dari titik akhir |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
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
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X dari titik arah |
| y1 | float | Koordinat Y dari titik arah |
| x2 | float | Koordinat X dari titik akhir |
| y2 | float | Koordinat Y dari titik akhir |
| index | long | Indeks segmen dalam PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Menutup gambar saat ini dari jalur ini

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

Mengatur posisi titik berikutnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Posisi titik |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Mengatur posisi titik berikutnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari titik |
| y | float | Koordinat Y dari titik |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Menambahkan busur yang ditentukan ke jalur.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | float | Lebar persegi panjang |
| heigth | float | Tinggi persegi panjang |
| startAngle | float | Sudut mulai. |
| sweepAngle | float | Sudut sapuan |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Mengatur mode isi

**Mengembalikan:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Mengatur mode isi

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Mengatur tampilan stroke

**Mengembalikan:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Mengatur tampilan stroke

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |