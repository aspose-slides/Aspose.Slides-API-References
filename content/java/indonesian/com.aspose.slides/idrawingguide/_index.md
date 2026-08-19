---
title: IDrawingGuide
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili panduan gambar yang dapat disesuaikan.
type: docs
url: /id/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Mewakili panduan gambar yang dapat disesuaikan.
## Metode

| Method | Description |
| --- | --- |
| [getOrientation()](#getOrientation--) | Returns or sets orientation of the drawing guide. |
| [setOrientation(byte value)](#setOrientation-byte-) | Returns or sets orientation of the drawing guide. |
| [getPosition()](#getPosition--) | Returns or sets position of the drawing guide in points from the top, left corner of the slide. |
| [setPosition(float value)](#setPosition-float-) | Returns or sets position of the drawing guide in points from the top, left corner of the slide. |
| [getColor()](#getColor--) | Returns or sets color of the drawing guide. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Returns or sets color of the drawing guide. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

Mengembalikan atau mengatur orientasi panduan gambar. Read/write [Orientation](../../com.aspose.slides/orientation).

**Mengembalikan:**  
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

Mengembalikan atau mengatur orientasi panduan gambar. Read/write [Orientation](../../com.aspose.slides/orientation).

**Parameter:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Mengembalikan atau mengatur posisi panduan gambar dalam poin dari sudut kiri atas slide. Read/write float.

--------------------

Rentang nilai tipikal adalah dari nol hingga tinggi slide untuk panduan horizontal dan dari nol hingga lebar slide untuk panduan vertikal.

**Mengembalikan:**  
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Mengembalikan atau mengatur posisi panduan gambar dalam poin dari sudut kiri atas slide. Read/write float.

--------------------

Rentang nilai tipikal adalah dari nol hingga tinggi slide untuk panduan horizontal dan dari nol hingga lebar slide untuk panduan vertikal.

**Parameter:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Mengembalikan atau mengatur warna panduan gambar. Read/write java.awt.Color.

**Mengembalikan:**  
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Mengembalikan atau mengatur warna panduan gambar. Read/write java.awt.Color.

**Parameter:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |