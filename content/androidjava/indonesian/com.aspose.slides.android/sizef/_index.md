---
title: SizeF
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Kelas untuk mendeskripsikan dimensi lebar dan tinggi dalam satuan arbitrer dengan nilai floating-point.
type: docs
url: /id/com.aspose.slides.android/sizef/
---
**Pewarisan:**
java.lang.Object
```
public class SizeF
```

Kelas untuk mendeskripsikan dimensi lebar dan tinggi dalam satuan arbitrer dengan nilai floating-point.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Membuat instance SizeF baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWidth()](#getWidth--) | Mendapatkan lebar ukuran. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi ukuran. |
| [equals(Object obj)](#equals-java.lang.Object-) | Memeriksa apakah ukuran ini sama dengan ukuran lain. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Mengembalikan ukuran sebagai string dengan format "WxH" |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

Membuat instance SizeF baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | float | Lebar ukuran |
| height | float | Tinggi ukuran |

### getWidth() {#getWidth--}
```
public float getWidth()
```

Mendapatkan lebar ukuran.

**Mengembalikan:**
float - lebar

### getHeight() {#getHeight--}
```
public float getHeight()
```

Mendapatkan tinggi ukuran.

**Mengembalikan:**
float - tinggi

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Memeriksa apakah ukuran ini sama dengan ukuran lain.

Dua ukuran dianggap sama jika dan hanya jika lebar dan tinggi keduanya sama.

Untuk tujuan ini, nilai float lebar/tinggi dianggap sama jika dan hanya jika metode Float\#floatToIntBits(float).floatToIntBits(float) mengembalikan nilai int yang identik ketika diterapkan pada masing-masing.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Mengembalikan:**
boolean - true jika objek-objek itu sama, false jika tidak

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

Mengembalikan ukuran sebagai string dengan format "WxH"

**Mengembalikan:**
java.lang.String - representasi string dari ukuran