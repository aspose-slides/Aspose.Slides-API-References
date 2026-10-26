---
title: IDrawingGuidesCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi panduan gambar yang dapat disesuaikan.
type: docs
url: /id/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Mewakili koleksi panduan gambar yang dapat disesuaikan.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan panduan gambar berdasarkan indeks. |
| [add(byte orientation, float position)](#add-byte-float-) | Menambahkan panduan gambar di akhir koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus panduan gambar pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [getCount()](#getCount--) | Mendapatkan jumlah semua elemen dalam koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Mengembalikan panduan gambar berdasarkan indeks. Baca-saja [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

Menambahkan panduan gambar di akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| orientation | byte | Orientasi panduan gambar. |
| position | float | Posisi panduan gambar dalam point. |

**Mengembalikan:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus panduan gambar pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks panduan gambar yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua elemen dari koleksi.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Mendapatkan jumlah semua elemen dalam koleksi. Baca-saja int.

**Mengembalikan:**
int