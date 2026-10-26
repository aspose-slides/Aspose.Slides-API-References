---
title: IColorOperationCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili kumpulan operasi transformasi warna.
type: docs
url: /id/com.aspose.slides/icoloroperationcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Mewakili kumpulan operasi transformasi warna.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan atau mengatur operasi pada indeks yang ditentukan. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Mengembalikan atau mengatur operasi pada indeks yang ditentukan. |
| [add(int operation, float parameter)](#add-int-float-) | Menambahkan operasi baru ke akhir koleksi. |
| [add(int operation)](#add-int-) | Menambahkan operasi baru ke akhir koleksi. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Menyisipkan operasi baru ke dalam koleksi. |
| [insert(int position, int operation)](#insert-int-int-) | Menyisipkan operasi baru ke dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus operasi warna dari koleksi. |
| [clear()](#clear--) | Menghapus semua operasi warna. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Mengembalikan atau mengatur operasi pada indeks yang ditentukan. Baca/tulis [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Mengembalikan atau mengatur operasi pada indeks yang ditentukan. Baca/tulis [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Menambahkan operasi baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operation | int | Tipe operasi. |
| parameter | float | Parameter operasi. |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operasi yang ditambahkan.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Menambahkan operasi baru ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| operation | int | Tipe operasi. |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operasi yang ditambahkan.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Menyisipkan operasi baru ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | int | Indeks tempat operasi akan disisipkan. |
| operation | int | Tipe operasi. |
| parameter | float | Parameter operasi. |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operasi yang disisipkan.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Menyisipkan operasi baru ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | int | Indeks tempat operasi akan disisipkan. |
| operation | int | Tipe operasi. |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operasi yang disisipkan.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus operasi warna dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks operasi warna yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua operasi warna.