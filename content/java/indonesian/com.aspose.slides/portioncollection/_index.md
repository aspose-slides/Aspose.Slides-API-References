---
title: PortionCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi bagian.
type: docs
url: /id/com.aspose.slides/portioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Mewakili koleksi bagian.
## Metode

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [isReadOnly()](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) hanya baca. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Menambahkan Portion ke akhir koleksi. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Menentukan indeks dari item tertentu dalam List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Menyisipkan Portion ke dalam koleksi pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, dimulai pada indeks Array tertentu. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Menghapus kemunculan pertama dari objek tertentu dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### getCount() {#getCount--}
```
public final int getCount()
```


Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Hanya baca int.

**Mengembalikan:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) hanya baca. Hanya baca boolean.

**Mengembalikan:**
boolean - true jika [IGenericCollection](../../com.aspose.slides/igenericcollection) hanya baca; selainnya false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```


Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Menambahkan Portion ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion yang akan ditambahkan ke akhir koleksi. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


Menentukan indeks dari item tertentu dalam List.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objek yang akan dicari dalam List. |

**Mengembalikan:**
int - Indeks dari item jika ditemukan dalam list; jika tidak, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```


Menyisipkan Portion ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol di mana Portion harus disisipkan. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion yang akan disisipkan. |

### clear() {#clear--}
```
public final void clear()
```


Menghapus semua elemen dari koleksi.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```


Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objek yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection); selainnya false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, dimulai pada indeks Array tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Array satu dimensi yang menjadi tujuan elemen yang disalin dari [IGenericCollection](../../com.aspose.slides/igenericcollection). Array harus memiliki indeks berbasis nol. |
| arrayIndex | int | Indeks berbasis nol dalam array di mana penyalinan dimulai. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


Menghapus kemunculan pertama dari objek tertentu dari [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objek yang akan dihapus dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item berhasil dihapus dari [IGenericCollection](../../com.aspose.slides/igenericcollection); selainnya false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection) asli.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Sebuah java.util.Iterator untuk seluruh koleksi.