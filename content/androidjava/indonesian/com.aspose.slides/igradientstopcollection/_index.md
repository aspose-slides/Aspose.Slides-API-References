---
title: IGradientStopCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi gradient stop.
type: docs
url: /id/com.aspose.slides/igradientstopcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Mewakili koleksi gradient stop.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan gradient stop berdasarkan indeks. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus gradient stop pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua gradient stop dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Mengembalikan gradient stop berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

Membuat gradient stop baru dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | float | Posisi gradient stop baru. |
| color | java.lang.Integer | Warna gradient stop baru. |

**Mengembalikan:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks gradient stop baru dalam koleksi.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
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
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Membuat gradient stop baru dan menambahkannya ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | float | Posisi gradient stop baru. |
| schemeColor | int | Warna gradient stop baru. |

**Mengembalikan:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks gradient stop baru dalam koleksi.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks dalam koleksi tempat gradient stop baru akan disisipkan. |
| position | float | Posisi gradient stop baru. |
| color | java.lang.Integer | Warna gradient stop baru. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
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
public abstract void insertSchemeColor(int index, float position, int schemeColor)
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
public abstract void removeAt(int index)
```

Menghapus gradient stop pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks gradient stop yang harus dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua gradient stop dari koleksi.