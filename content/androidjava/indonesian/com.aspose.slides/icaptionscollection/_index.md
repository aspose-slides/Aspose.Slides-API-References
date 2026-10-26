---
title: ICaptionsCollection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili sebuah koleksi caption tertutup.
type: docs
url: /id/com.aspose.slides/icaptionscollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Mewakili sebuah koleksi caption tertutup.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan caption tertutup pada indeks yang ditentukan. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Menambahkan caption tertutup WebVTT ke akhir koleksi. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Menambahkan caption tertutup WebVTT ke akhir koleksi dari aliran. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Menghapus caption tertutup yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus caption tertutup pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua caption tertutup dari koleksi. |
| [getCount()](#getCount--) | Mengembalikan jumlah elemen dalam koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
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
public abstract ICaptions add(String label, String filePath)
```

Menambahkan caption tertutup WebVTT ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | java.lang.String | Label caption tertutup. |
| filePath | java.lang.String | Jalur ke file WebVTT. |

**Mengembalikan:**
[ICaptions](../../com.aspose.slides/icaptions) - Instance [ICaptions](../../com.aspose.slides/icaptions) yang ditambahkan.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

Menambahkan caption tertutup WebVTT ke akhir koleksi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | java.lang.String | Label caption tertutup. |
| stream | java.io.InputStream | Aliran masukan yang berisi data dalam format WebVTT. |

**Mengembalikan:**
[ICaptions](../../com.aspose.slides/icaptions) - Instance [ICaptions](../../com.aspose.slides/icaptions) yang ditambahkan.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

Menghapus caption tertutup yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Caption tertutup yang akan dihapus. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus caption tertutup pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks caption tertutup yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua caption tertutup dari koleksi.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Mengembalikan jumlah elemen dalam koleksi. Hanya-baca int .

**Mengembalikan:**
int