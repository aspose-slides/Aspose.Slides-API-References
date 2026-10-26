---
title: IPortionCollection
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili sebuah koleksi Portion.
type: docs
url: /id/com.aspose.slides/iportioncollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Mewakili sebuah koleksi Portion.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [getCount()](#getCount--) | Mengambil jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Menambahkan Portion ke akhir koleksi. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Menentukan indeks dari Portion tertentu dalam koleksi. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Menyisipkan Portion ke dalam koleksi pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Menghapus kemunculan pertama dari objek tertentu dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Mengambil elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Mengambil jumlah elemen yang sebenarnya terkandung dalam koleksi. int baca-saja.

**Mengembalikan:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Menambahkan Portion ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion yang akan ditambahkan ke akhir koleksi. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Menentukan indeks dari Portion tertentu dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Portion yang akan dicari dalam koleksi. |

**Mengembalikan:**
int - Indeks item jika ditemukan dalam koleksi; jika tidak, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Menyisipkan Portion ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat Portion harus disisipkan. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion yang akan disisipkan. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua elemen dari koleksi.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objek yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item ditemukan di [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Menghapus kemunculan pertama dari objek tertentu dari [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objek yang akan dihapus dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item berhasil dihapus dari [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection) asli.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |