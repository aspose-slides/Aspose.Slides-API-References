---
title: ShapeFrame
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili properti bingkai bentuk.
type: docs
url: /id/com.aspose.slides/shapeframe/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Mewakili properti bingkai bentuk.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Membuat properti bingkai bentuk baru. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getX()](#getX--) | Mengembalikan koordinat X dari sudut kiri atas sebuah bingkai. |
| [getY()](#getY--) | Mengembalikan koordinat Y dari sudut kiri atas sebuah bingkai. |
| [getWidth()](#getWidth--) | Mengembalikan lebar sebuah bingkai. |
| [getHeight()](#getHeight--) | Mengembalikan tinggi sebuah bingkai. |
| [getRotation()](#getRotation--) | Mengembalikan jumlah derajat bingkai diputar sekitar sumbu z. |
| [getCenterX()](#getCenterX--) | Mengembalikan koordinat X dari pusat sebuah bingkai. |
| [getCenterY()](#getCenterY--) | Mengembalikan koordinat Y dari pusat sebuah bingkai. |
| [getFlipH()](#getFlipH--) | Menentukan apakah sebuah bingkai dibalik secara horizontal. |
| [getFlipV()](#getFlipV--) | Menentukan apakah sebuah bingkai dibalik secara vertikal. |
| [getRectangle()](#getRectangle--) | Mengembalikan koordinat sebuah bingkai. |
| [deepClone()](#deepClone--) | Membuat klon |
| [cloneT()](#cloneT--) | Membuat klon. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Membuat properti bingkai bentuk baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari sebuah bingkai. |
| y | float | Koordinat Y dari sebuah bingkai. |
| width | float | Lebar sebuah bingkai. |
| height | float | Tinggi sebuah bingkai. |
| flipH | byte | Benar jika sebuah bingkai dibalik secara horizontal. |
| flipV | byte | Benar jika sebuah bingkai dibalik secara vertikal. |
| rotationAngle | float | Jumlah derajat bingkai diputar. |

### getX() {#getX--}
```
public final float getX()
```

Mengembalikan koordinat X dari sudut kiri atas sebuah bingkai. Baca-saja float.

**Mengembalikan:**
float
### getY() {#getY--}
```
public final float getY()
```

Mengembalikan koordinat Y dari sudut kiri atas sebuah bingkai. Baca-saja float.

**Mengembalikan:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Mengembalikan lebar sebuah bingkai. Baca-saja float.

**Mengembalikan:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Mengembalikan tinggi sebuah bingkai. Baca-saja float.

**Mengembalikan:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Mengembalikan jumlah derajat bingkai diputar sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam. Baca-saja float.

**Mengembalikan:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Mengembalikan koordinat X dari pusat sebuah bingkai. Baca-saja float.

**Mengembalikan:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Mengembalikan koordinat Y dari pusat sebuah bingkai. Baca-saja float.

**Mengembalikan:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Menentukan apakah sebuah bingkai dibalik secara horizontal. Baca-saja [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Menentukan apakah sebuah bingkai dibalik secara vertikal. Baca-saja [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Mengembalikan koordinat sebuah bingkai. Baca-saja android.graphics.RectF.

**Mengembalikan:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Membuat klon

**Mengembalikan:**
java.lang.Object - Bingkai bentuk yang diklon.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Membuat klon.

**Mengembalikan:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Bingkai bentuk yang diklon.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Mengembalikan:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang dibandingkan dengan instance ini. |

**Mengembalikan:**
boolean - **true** jika obj adalah ShapeFrame yang memiliki nilai yang sama dengan instance ini; jika tidak, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx yang dibandingkan dengan instance ini. |

**Mengembalikan:**
boolean - **true** jika value adalah ShapeFrame yang memiliki nilai yang sama dengan instance ini; jika tidak, **false**.