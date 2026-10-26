---
title: Size
second_title: Referensi API Java Aspose.Slides untuk Android
description: Kelas untuk mendeskripsikan dimensi lebar dan tinggi dalam satuan arbitrer.
type: docs
url: /id/com.aspose.slides.android/size/
---
**Pewarisan:**
java.lang.Object
```
public class Size
```

Kelas untuk mendeskripsikan dimensi lebar dan tinggi dalam satuan arbitrer.
## Constructors

| Constructor | Description |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Membuat sebuah instance Size baru. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Mengambil lebar dari ukuran. |
| [getHeight()](#getHeight--) | Mengambil tinggi dari ukuran. |
| [equals(Object obj)](#equals-java.lang.Object-) | Memeriksa apakah ukuran ini sama dengan ukuran lain. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Mengembalikan ukuran yang direpresentasikan sebagai string dengan format  "WxH"  |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Membuat sebuah instance Size baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Lebar ukuran |
| height | int | Tinggi ukuran |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Mengambil lebar dari ukuran.

**Mengembalikan:**
int - lebar
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mengambil tinggi dari ukuran.

**Mengembalikan:**
int - tinggi
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Memeriksa apakah ukuran ini sama dengan ukuran lain.

Dua ukuran sama jika dan hanya jika lebar dan tinggi keduanya sama.

Objek ukuran tidak pernah sama dengan tipe objek lain.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Mengembalikan:**
boolean -  true  jika objek-objek tersebut sama,  false  jika tidak
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Mengembalikan:**
int
### toString() {#toString--}
```
public String toString()
```


Mengembalikan ukuran yang direpresentasikan sebagai string dengan format  "WxH" 

**Mengembalikan:**
java.lang.String - representasi string dari ukuran