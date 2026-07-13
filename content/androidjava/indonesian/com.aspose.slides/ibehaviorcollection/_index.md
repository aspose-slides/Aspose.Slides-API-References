---
title: IBehaviorCollection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili kumpulan efek perilaku.
type: docs
url: /id/com.aspose.slides/ibehaviorcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Mewakili kumpulan efek perilaku.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan perilaku pada indeks yang ditentukan. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Mengembalikan perilaku pada indeks yang ditentukan. |
| [getCount()](#getCount--) | Mengembalikan jumlah perilaku dalam sebuah koleksi. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Menambahkan perilaku baru ke koleksi. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Menentukan indeks item tertentu dalam List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Menyisipkan perilaku baru ke koleksi pada indeks yang ditentukan. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Menghapus perilaku yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus perilaku dari koleksi pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua perilaku dari koleksi. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Mengembalikan perilaku pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks perilaku yang akan dikembalikan. |

**Mengembalikan:**
[IBehavior](../../com.aspose.slides/ibehavior) - Perilaku animasi.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Mengembalikan perilaku pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks perilaku yang akan dikembalikan. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Mengembalikan jumlah perilaku dalam sebuah koleksi. Hanya-baca int.

**Mengembalikan:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Menambahkan perilaku baru ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Perilaku yang akan ditambahkan. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Menentukan indeks item tertentu dalam List.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objek yang akan dicari dalam List. |

**Mengembalikan:**
int - Indeks item jika ditemukan dalam list; jika tidak, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Menyisipkan perilaku baru ke koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks dimana perilaku baru harus disisipkan. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Perilaku yang akan disisipkan. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Menghapus perilaku yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Perilaku yang akan dihapus. |

**Mengembalikan:**
boolean - True jika perilaku berhasil dihapus boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus perilaku dari koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks perilaku yang akan dihapus. |
### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua perilaku dari koleksi.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objek yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false.