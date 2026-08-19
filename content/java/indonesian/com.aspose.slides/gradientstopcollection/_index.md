---
title: GradientStopCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan gradient stop.
type: docs
url: /id/com.aspose.slides/gradientstopcollection/
---
**Pewarisan:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)  
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Mewakili sebuah koleksi gradient stop.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Mengembalikan jumlah gradient stop dalam sebuah koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan gradient stop berdasarkan indeks. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus gradient stop pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua gradient stop dari koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long

### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah gradient stop dalam sebuah koleksi. Hanya-baca int .

**Mengembalikan:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Mengembalikan gradient stop berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```

Membuat gradient stop baru dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | float | Posisi gradient stop baru. |
| color | java.awt.Color | Warna gradient stop baru. |

**Mengembalikan:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks gradient stop baru dalam koleksi.

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Membuat gradient stop baru dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | float | Posisi gradient stop baru. |
| presetColor | int | Warna gradient stop baru. |

**Mengembalikan:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks gradient stop baru dalam koleksi.

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Membuat gradient stop baru dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | float | Posisi gradient stop baru. |
| schemeColor | int | Warna gradient stop baru. |

**Mengembalikan:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks gradient stop baru dalam koleksi.

### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```

Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks dalam koleksi tempat gradient stop baru akan disisipkan. |
| position | float | Posisi gradient stop baru. |
| color | java.awt.Color | Warna gradient stop baru. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks dalam koleksi tempat gradient stop baru akan disisipkan. |
| position | float | Posisi gradient stop baru. |
| presetColor | int | Warna gradient stop baru. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks dalam koleksi tempat gradient stop baru akan disisipkan. |
| position | float | Posisi gradient stop baru. |
| schemeColor | int | Warna gradient stop baru. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus gradient stop pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks gradient stop yang harus dihapus. |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua gradient stop dari koleksi.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Sebuah java.util.Iterator untuk seluruh koleksi.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). Hanya-baca boolean .

**Mengembalikan:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object