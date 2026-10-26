---
title: ColorOperation
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili berbagai operasi warna yang digunakan untuk transformasi warna.
type: docs
url: /id/com.aspose.slides/coloroperation/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Mewakili operasi warna yang berbeda yang digunakan untuk transformasi warna. Objek tidak dapat diubah.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Membuat operasi transformasi warna baru. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Membuat operasi transformasi warna baru. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOperationType()](#getOperationType--) | Mengembalikan atau mengatur jenis operasi. |
| [getParameter()](#getParameter--) | Mengembalikan parameter sebuah operasi. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua instance ColorOperation sama. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Membuat operasi transformasi warna baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| op | int | Jenis operasi. |
### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Membuat operasi transformasi warna baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| op | int | Jenis operasi. |
| parameter | float | Parameter operasi. |
### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Mengembalikan atau mengatur jenis operasi. Baca-saja [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Mengembalikan:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Mengembalikan parameter sebuah operasi. Baca-saja float.

**Mengembalikan:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah dua instance ColorOperation sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation yang akan dibandingkan dengan ColorOperation saat ini. |

**Mengembalikan:**
boolean - **true** jika ColorOperation yang ditentukan sama dengan ColorOperation saat ini; jika tidak, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.

**Mengembalikan:**
int