---
title: CustomXmlPartCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi bagian xml khusus.
type: docs
url: /id/com.aspose.slides/customxmlpartcollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Mewakili koleksi bagian xml khusus.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan elemen pada indeks yang ditentukan. |
| [size()](#size--) | Mengembalikan jumlah bagian xml khusus dalam koleksi. |
| [add(String xmlString)](#add-java.lang.String-) | Menambahkan bagian xml khusus baru. |
| [add(byte[] xmlData)](#add-byte---) | Menambahkan bagian xml khusus baru. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Menambahkan bagian xml khusus baru. |
| [removeAt(int index)](#removeAt-int-) | Menghapus bagian xml khusus pada indeks yang ditentukan. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Menghapus kemunculan pertama dari objek tertentu dalam koleksi. |
| [clear()](#clear--) | Menghapus semua item dari koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```


Mengembalikan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan diambil. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Elemen pada indeks yang ditentukan.
### size() {#size--}
```
public final int size()
```


Mengembalikan jumlah bagian xml khusus dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```


Menambahkan bagian xml khusus baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlString | java.lang.String | String xml dari bagian baru yang akan ditambahkan. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Bagian xml khusus yang dibuat.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```


Menambahkan bagian xml khusus baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlData | byte[] | Data xml dari bagian baru yang akan ditambahkan. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Bagian xml khusus yang dibuat.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```


Menambahkan bagian xml khusus baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream dengan data xml dari bagian baru yang akan ditambahkan. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Bagian xml khusus yang dibuat.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus bagian xml khusus pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```


Menghapus kemunculan pertama dari objek tertentu dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Bagian xml khusus yang akan dihapus. |

**Mengembalikan:**
boolean - true jika item berhasil dihapus; jika tidak, false.
### clear() {#clear--}
```
public final void clear()
```


Menghapus semua item dari koleksi.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array tujuan penyalinan. |
| index | int | Indeks untuk memulai penyalinan. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Hanya-baca boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - java.util.Iterator untuk seluruh koleksi.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject