---
title: CaptionsCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan closed caption.
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

Mewakili kumpulan closed caption.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan closed caption pada indeks yang ditentukan. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Menambahkan closed caption WebVTT ke akhir koleksi. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Menambahkan closed caption WebVTT ke akhir koleksi dari aliran. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Menghapus closed caption yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus closed caption pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua closed caption dari koleksi. |
| [getCount()](#getCount--) | Mengembalikan jumlah elemen dalam koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Mengembalikan closed caption pada indeks yang ditentukan. Hanya-baca [ICaptions](../../com.aspose.slides/icaptions).

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


Menambahkan closed caption WebVTT ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | java.lang.String | Label closed caption. |
| filePath | java.lang.String | Path ke file WebVTT. |

**Mengembalikan:**
[ICaptions](../../com.aspose.slides/icaptions) - Instansi [ICaptions](../../com.aspose.slides/icaptions) yang ditambahkan.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


Menambahkan closed caption WebVTT ke akhir koleksi dari aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | java.lang.String | Label closed caption. |
| stream | java.io.InputStream | Aliran input yang berisi data dalam format WebVTT. |

**Mengembalikan:**
[ICaptions](../../com.aspose.slides/icaptions) - Instansi [ICaptions](../../com.aspose.slides/icaptions) yang ditambahkan.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Menghapus closed caption yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Closed caption yang akan dihapus. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus closed caption pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks closed caption yang akan dihapus. |

### clear() {#clear--}
```
public final void clear()
```


Menghapus semua closed caption dari koleksi.

### getCount() {#getCount--}
```
public final int getCount()
```


Mengembalikan jumlah elemen dalam koleksi. Hanya-baca int .

**Mengembalikan:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Sebuah System.Collections.Generic.IEnumerator1 yang dapat digunakan untuk mengiterasi koleksi.