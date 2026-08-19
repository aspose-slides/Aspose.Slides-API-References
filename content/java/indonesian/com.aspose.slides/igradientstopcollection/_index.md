---
title: IGradientStopCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kumpulan gradient stop.
type: docs
url: /id/com.aspose.slides/igradientstopcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Mewakili kumpulan gradient stop.
## Metode

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan gradient stop berdasarkan indeks. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Membuat gradient stop baru dan menambahkannya ke akhir koleksi. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus gradient stop pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua gradient stop dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Mengembalikan gradient stop berdasarkan indeks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Membuat gradient stop baru dan menambahkannya ke akhir koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Posisi gradient stop baru. |
| color | java.awt.Color | Warna gradient stop baru. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks gradient stop baru dalam koleksi.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Membuat gradient stop baru dan menambahkannya ke akhir koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Posisi gradient stop baru. |
| presetColor | int | Warna gradient stop baru. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks gradient stop baru dalam koleksi.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Membuat gradient stop baru dan menambahkannya ke akhir koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Posisi gradient stop baru. |
| schemeColor | int | Warna gradient stop baru. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks gradient stop baru dalam koleksi.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks dalam koleksi tempat gradient stop baru akan disisipkan. |
| position | float | Posisi gradient stop baru. |
| color | java.awt.Color | Warna gradient stop baru. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks dalam koleksi tempat gradient stop baru akan disisipkan. |
| position | float | Posisi gradient stop baru. |
| presetColor | int | Warna gradient stop baru. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Membuat gradient stop baru dan menyisipkannya pada indeks yang ditentukan ke dalam koleksi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks dalam koleksi tempat gradient stop baru akan disisipkan. |
| position | float | Posisi gradient stop baru. |
| schemeColor | int | Warna gradient stop baru. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus gradient stop pada indeks yang ditentukan.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks gradient stop yang harus dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua gradient stop dari koleksi.