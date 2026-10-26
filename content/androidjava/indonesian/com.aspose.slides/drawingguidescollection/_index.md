---
title: DrawingGuidesCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi panduan gambar yang dapat disesuaikan.
type: docs
url: /id/com.aspose.slides/drawingguidescollection/
---
**Warisan:**  
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)  
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Mewakili koleksi panduan gambar yang dapat disesuaikan.
## Metode

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan panduan gambar berdasarkan indeks. |
| [add(byte orientation, float position)](#add-byte-float-) | Menambahkan panduan gambar di akhir koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus panduan gambar pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [getCount()](#getCount--) | Mengembalikan jumlah elemen dalam koleksi. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


Mengembalikan panduan gambar berdasarkan indeks. Hanya-baca [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


Menambahkan panduan gambar di akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| orientation | byte | Orientasi panduan gambar. |
| position | float | Posisi panduan gambar dalam poin. |

**Mengembalikan:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus panduan gambar pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks panduan gambar yang harus dihapus. |

### clear() {#clear--}
```
public final void clear()
```


Menghapus semua elemen dari koleksi.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Sebuah java.util.Iterator untuk seluruh koleksi.
### getCount() {#getCount--}
```
public final int getCount()
```


Mengembalikan jumlah elemen dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Array target. |
| index | int | Indeks awal dalam array target. |