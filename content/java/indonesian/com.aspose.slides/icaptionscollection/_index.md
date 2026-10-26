---
title: ICaptionsCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi caption tertutup.
type: docs
url: /id/com.aspose.slides/icaptionscollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Mewakili koleksi caption tertutup.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the closed captions at the specified index. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Adds WebVTT closed captions to the end of the collection. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Adds WebVTT closed captions to the end of the collection from a stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Removes the specified closed captions from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the closed captions at the specified index. |
| [clear()](#clear--) | Removes all closed captions from the collection. |
| [getCount()](#getCount--) | Returns the number of elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

Mengembalikan caption tertutup pada indeks yang ditentukan. Hanya baca [ICaptions](../../com.aspose.slides/icaptions).

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
| label | java.lang.String | Label dari caption tertutup. |
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
| label | java.lang.String | Label dari caption tertutup. |
| stream | java.io.InputStream | Aliran input yang berisi data dalam format WebVTT. |

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
| index | int | Indeks dari caption tertutup yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua caption tertutup dari koleksi.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Mengembalikan jumlah elemen dalam koleksi. Hanya baca  int .

**Mengembalikan:**
int