---
title: IColorOperationCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi operasi transformasi warna.
type: docs
url: /id/com.aspose.slides/icoloroperationcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Mewakili koleksi operasi transformasi warna.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns or sets the operation at the specified index. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Returns or sets the operation at the specified index. |
| [add(int operation, float parameter)](#add-int-float-) | Adds a new operation to the end of collection. |
| [add(int operation)](#add-int-) | Adds a new operation to the end of collection. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserts the new operation to a collection. |
| [insert(int position, int operation)](#insert-int-int-) | Inserts the new operation to a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the color operation from a collection. |
| [clear()](#clear--) | Removes all color operations. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```


Returns or sets the operation at the specified index. Baca/tulis [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```


Returns or sets the operation at the specified index. Baca/tulis [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```


Menambahkan operasi baru ke akhir koleksi.

**Parameter:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks operasi warna yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua operasi warna.