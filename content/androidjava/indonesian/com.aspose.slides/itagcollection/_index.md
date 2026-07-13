---
title: ITagCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi tag pasangan string yang ditentukan pengguna
type: docs
url: /id/com.aspose.slides/itagcollection/
---
**Semua Interface yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Mewakili koleksi tag (pasangan string yang ditentukan pengguna)
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Menambahkan tag baru ke koleksi. |
| [remove(String name)](#remove-java.lang.String-) | Menghapus tag dengan nama tertentu dari koleksi. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Mengembalikan indeks berbasis nol dari kunci yang ditentukan dalam koleksi. |
| [contains(String name)](#contains-java.lang.String-) | Menentukan apakah koleksi berisi nama tertentu. |
| [removeAt(int index)](#removeAt-int-) | Menghapus tag pada indeks tertentu. |
| [clear()](#clear--) | Menghapus semua tag dari koleksi. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Mengembalikan nilai tag pada indeks tertentu. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Mengembalikan kunci tag pada indeks tertentu. |
| [getNamesOfTags()](#getNamesOfTags--) | Mengembalikan nama-nama tag. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Mengembalikan atau mengatur pasangan kunci dan nilai dari sebuah tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Mengembalikan atau mengatur pasangan kunci dan nilai dari sebuah tag. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```


Menambahkan tag baru ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama tag. |
| value | java.lang.String | Nilai tag. |

**Mengembalikan:**
int - Indeks tag yang ditambahkan.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Menghapus tag dengan nama tertentu dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama tag yang akan dihapus. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```


Mengembalikan indeks berbasis nol dari kunci yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama yang akan dicari dalam koleksi. |

**Mengembalikan:**
int - Indeks berbasis nol dari kunci, jika kunci ditemukan dalam koleksi; jika tidak, -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```


Menentukan apakah koleksi berisi nama tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Kunci yang akan dicari. |

**Mengembalikan:**
boolean - True jika koleksi berisi tag dengan kunci yang ditentukan; jika tidak, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus tag pada indeks tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari tag yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua tag dari koleksi.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Mengembalikan nilai tag pada indeks tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tag yang akan dikembalikan. |

**Mengembalikan:**
java.lang.String - Nilai tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Mengembalikan kunci tag pada indeks tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tag yang akan dikembalikan. |

**Mengembalikan:**
java.lang.String - Kunci tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Mengembalikan nama-nama tag.

**Mengembalikan:**
java.lang.String[] - Nama-nama tag.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Mengembalikan atau mengatur pasangan kunci dan nilai dari sebuah tag.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Kunci tag. |

**Mengembalikan:**
java.lang.String - Nilai tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Mengembalikan atau mengatur pasangan kunci dan nilai dari sebuah tag.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Kunci tag. |
| value | java.lang.String |  |