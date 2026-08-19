---
title: IDrawingGuidesCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan panduan gambar yang dapat disesuaikan.
type: docs
url: /id/com.aspose.slides/idrawingguidescollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Mewakili kumpulan panduan gambar yang dapat disesuaikan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan panduan gambar berdasarkan indeks. |
| [add(byte orientation, float position)](#add-byte-float-) | Menambahkan panduan gambar di akhir kumpulan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus panduan gambar pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari kumpulan. |
| [getCount()](#getCount--) | Mendapatkan jumlah semua elemen dalam kumpulan. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
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
public abstract IDrawingGuide add(byte orientation, float position)
```

Menambahkan panduan gambar di akhir kumpulan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| orientation | byte | Orientasi panduan gambar. |
| position | float | Posisi panduan gambar dalam poin. |

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
| index | int | Indeks panduan gambar yang harus dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua elemen dari kumpulan.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Mendapatkan jumlah semua elemen dalam kumpulan. Hanya-baca int.

**Mengembalikan:**
int