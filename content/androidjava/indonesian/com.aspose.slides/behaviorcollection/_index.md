---
title: BehaviorCollection
second_title: Aspose.Slides untuk Android via Java API Reference
description: Mewakili koleksi efek perilaku.
type: docs
url: /id/com.aspose.slides/behaviorcollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Mewakili koleksi efek perilaku.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCount()](#getCount--) | Mengembalikan jumlah perilaku dalam koleksi. |
| [isReadOnly()](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat baca-saja. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Menambahkan perilaku baru ke dalam koleksi. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Menentukan indeks dari item tertentu dalam List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Menyisipkan perilaku baru ke dalam koleksi pada indeks yang ditentukan. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Menyalin elemen-elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, dimulai pada indeks Array tertentu. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Menghapus perilaku yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus perilaku dari koleksi pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua perilaku dari koleksi. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan perilaku pada indeks yang ditentukan. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Menetapkan perilaku pada indeks yang ditentukan. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### getCount() {#getCount--}
```
public final int getCount()
```

Mengembalikan jumlah perilaku dalam koleksi. Baca-saja int.

**Mengembalikan:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat baca-saja. Baca-saja boolean.

**Mengembalikan:**
boolean - true jika [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat baca-saja; jika tidak, false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Menambahkan perilaku baru ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Perilaku yang akan ditambahkan. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Menentukan indeks dari item tertentu dalam List.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objek yang akan dicari dalam List. |

**Mengembalikan:**
int - Indeks item jika ditemukan dalam list; jika tidak, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Menyisipkan perilaku baru ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tempat perilaku baru akan disisipkan. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Perilaku yang akan disisipkan. |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Menyalin elemen-elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, dimulai pada indeks Array tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Array satu dimensi yang menjadi tujuan elemen yang disalin dari [IGenericCollection](../../com.aspose.slides/igenericcollection). Array harus berindeks nol. |
| arrayIndex | int | Indeks berbasis nol dalam array dimana penyalinan dimulai. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Menghapus perilaku yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Perilaku yang akan dihapus. |

**Mengembalikan:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus perilaku dari koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks perilaku yang akan dihapus. |
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua perilaku dari koleksi.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objek yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Mengembalikan perilaku pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks perilaku yang akan dikembalikan. |

**Mengembalikan:**
[IBehavior](../../com.aspose.slides/ibehavior) - perilaku animasi.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Menetapkan perilaku pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks perilaku yang akan dikembalikan. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Sebuah java.util.Iterator untuk seluruh koleksi.