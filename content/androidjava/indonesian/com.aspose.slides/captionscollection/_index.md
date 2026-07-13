---
title: CaptionsCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili kumpulan caption tertutup.
type: docs
url: /id/com.aspose.slides/captionscollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Mewakili kumpulan caption tertutup.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan caption tertutup pada indeks yang ditentukan. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Menambahkan caption tertutup WebVTT ke akhir kumpulan. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Menambahkan caption tertutup WebVTT ke akhir kumpulan dari aliran. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Menghapus caption tertutup yang ditentukan dari kumpulan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus caption tertutup pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua caption tertutup dari kumpulan. |
| [getCount()](#getCount--) | Mengembalikan jumlah elemen dalam kumpulan. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi melalui kumpulan. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Mengembalikan caption tertutup pada indeks yang ditentukan. Hanya-baca [ICaptions](../../com.aspose.slides/icaptions).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

Menambahkan caption tertutup WebVTT ke akhir kumpulan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | java.lang.String | Label caption tertutup. |
| filePath | java.lang.String | Jalur ke file WebVTT. |

**Mengembalikan:**
[ICaptions](../../com.aspose.slides/icaptions) - Instance [ICaptions](../../com.aspose.slides/icaptions) yang ditambahkan.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Menambahkan caption tertutup WebVTT ke akhir kumpulan dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | java.lang.String | Label caption tertutup. |
| stream | java.io.InputStream | Aliran masukan yang berisi data dalam format WebVTT. |

**Mengembalikan:**
[ICaptions](../../com.aspose.slides/icaptions) - Instance [ICaptions](../../com.aspose.slides/icaptions) yang ditambahkan.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Menghapus caption tertutup yang ditentukan dari kumpulan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Caption tertutup yang akan dihapus. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus caption tertutup pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks caption tertutup yang akan dihapus. |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua caption tertutup dari kumpulan.

### getCount() {#getCount--}
```
public final int getCount()
```

Mengembalikan jumlah elemen dalam kumpulan. Hanya-baca int .

**Mengembalikan:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Mengembalikan enumerator yang mengiterasi melalui kumpulan.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Sebuah System.Collections.Generic.IEnumerator1 yang dapat digunakan untuk mengiterasi melalui kumpulan.