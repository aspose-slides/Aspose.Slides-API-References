---
title: GeometryPath
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili jalur geometri dari GeometryShape
type: docs
url: /id/com.aspose.slides/geometrypath/
---
**Warisan:**
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
| [GeometryPath()](#GeometryPath--) | Membuat instance dari GeometryPath |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPathData()](#getPathData--) | Mengembalikan jalur geometri GeometryShape sebagai array segmen jalur. |
| [removeAt(int index)](#removeAt-int-) | Menghapus segmen pada indeks yang ditentukan dari jalur geometri. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Menambahkan garis ke akhir jalur |
| [lineTo(float x, float y)](#lineTo-float-float-) | Menambahkan garis ke akhir jalur |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Menambahkan garis ke tempat yang ditentukan pada jalur |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Menambahkan garis ke tempat yang ditentukan pada jalur |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Menambahkan kurva Bezier kubik di akhir jalur |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Menambahkan kurva Bezier kubik di akhir jalur |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Menambahkan kurva Bezier kuadratik di akhir jalur |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Menambahkan kurva Bezier kuadratik di akhir jalur |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur |
| [closeFigure()](#closeFigure--) | Menutup figure saat ini dari jalur ini |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Mengatur posisi titik berikutnya. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Mengatur posisi titik berikutnya. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Menambahkan busur yang ditentukan ke jalur. |
| [getFillMode()](#getFillMode--) | Mengatur mode isi |
| [setFillMode(byte value)](#setFillMode-byte-) | Mengatur mode isi |
| [getStroke()](#getStroke--) | Mengatur tampilan goresan |
| [setStroke(boolean value)](#setStroke-boolean-) | Mengatur tampilan goresan |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Membuat instance dari GeometryPath

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

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Menambahkan garis ke akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | android.graphics.PointF | Titik akhir garis |

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

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Menambahkan garis ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | android.graphics.PointF | Titik akhir |
| index | long | Indeks segmen dalam PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Menambahkan garis ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X titik |
| y | float | Koordinat Y titik |
| index | long | Indeks segmen dalam PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Menambahkan kurva Bezier kubik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | android.graphics.PointF | Titik arah pertama |
| point2 | android.graphics.PointF | Titik arah kedua |
| point3 | android.graphics.PointF | Titik akhir |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
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

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | android.graphics.PointF | Titik arah pertama |
| point2 | android.graphics.PointF | Titik arah kedua |
| point3 | android.graphics.PointF | Titik akhir |
| index | long | Indeks segmen dalam PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
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

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Menambahkan kurva Bezier kuadratik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | android.graphics.PointF | Titik arah |
| point2 | android.graphics.PointF | Titik akhir |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Menambahkan kurva Bezier kuadratik di akhir jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 | float | Koordinat X titik arah |
| y1 | float | Koordinat Y titik arah |
| x2 | float | Koordinat X titik akhir |
| y2 | float | Koordinat Y titik akhir |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | android.graphics.PointF | Titik arah |
| point2 | android.graphics.PointF | Titik akhir |
| index | long | Indeks segmen dalam PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
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
public final void closeFigure()
```

Menutup figure saat ini dari jalur ini

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Mengatur posisi titik berikutnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | android.graphics.PointF | Posisi titik |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Mengatur posisi titik berikutnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X titik |
| y | float | Koordinat Y titik |

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
| sweepAngle | float | Sudut putar |

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

Mengatur tampilan goresan

**Mengembalikan:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Mengatur tampilan goresan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |