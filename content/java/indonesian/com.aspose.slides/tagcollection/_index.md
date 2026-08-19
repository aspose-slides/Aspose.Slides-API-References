---
title: TagCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi tag berupa pasangan string yang didefinisikan pengguna
type: docs
url: /id/com.aspose.slides/tagcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Mewakili koleksi tag (pasangan string yang didefinisikan pengguna)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan jumlah tag dalam koleksi. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Menambahkan tag baru ke koleksi. |
| [remove(String name)](#remove-java.lang.String-) | Menghapus tag dengan nama tertentu dari koleksi. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Mengembalikan indeks berbasis nol dari kunci yang ditentukan dalam koleksi. |
| [contains(String name)](#contains-java.lang.String-) | Menentukan apakah koleksi berisi nama tertentu. |
| [removeAt(int index)](#removeAt-int-) | Menghapus tag pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua tag dari koleksi. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Mengembalikan nilai tag pada indeks yang ditentukan. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Mengembalikan kunci tag pada indeks yang ditentukan. |
| [getNamesOfTags()](#getNamesOfTags--) | Mengembalikan nama-nama tag. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Mengembalikan atau mengatur pasangan kunci dan nilai dari sebuah tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Mengembalikan atau mengatur pasangan kunci dan nilai dari sebuah tag. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah tag dalam koleksi. int hanya-baca.

**Mengembalikan:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Menambahkan tag baru ke koleksi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama tag. |
| value | java.lang.String | Nilai tag. |

**Mengembalikan:**
int - Indeks tag yang ditambahkan.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Menghapus tag dengan nama tertentu dari koleksi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama tag yang akan dihapus. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Mengembalikan indeks berbasis nol dari kunci yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama yang akan dicari dalam koleksi. |

**Mengembalikan:**
int - Indeks berbasis nol dari kunci, jika kunci ditemukan dalam koleksi; jika tidak, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Menentukan apakah koleksi berisi nama tertentu.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Kunci yang akan dicari. |

**Mengembalikan:**
boolean - True jika koleksi berisi tag dengan kunci yang ditentukan; jika tidak, false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus tag pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari tag yang akan dihapus. |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua tag dari koleksi.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Mengembalikan nilai tag pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tag yang akan dikembalikan. |

**Mengembalikan:**
java.lang.String - Nilai tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Mengembalikan kunci tag pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tag yang akan dikembalikan. |

**Mengembalikan:**
java.lang.String - Kunci tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Mengembalikan nama-nama tag.

**Mengembalikan:**
java.lang.String[] - Nama-nama tag.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Mengembalikan atau mengatur pasangan kunci dan nilai dari sebuah tag.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Kunci tag. |

**Mengembalikan:**
java.lang.String - Nilai tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Mengembalikan atau mengatur pasangan kunci dan nilai dari sebuah tag.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Kunci tag. |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array yang akan diisi. |
| index | int | Posisi mulai dalam array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). boolean hanya-baca.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Object hanya-baca.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Sebuah java.util.Iterator untuk seluruh koleksi.