---
title: CustomXmlPartCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi bagian custom xml.
type: docs
url: /id/com.aspose.slides/customxmlpartcollection/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Mewakili koleksi bagian custom xml.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan elemen pada indeks yang ditentukan. |
| [size()](#size--) | Mengembalikan jumlah bagian custom xml dalam koleksi. |
| [add(String xmlString)](#add-java.lang.String-) | Menambahkan bagian custom xml baru. |
| [add(byte[] xmlData)](#add-byte---) | Menambahkan bagian custom xml baru. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Menambahkan bagian custom xml baru. |
| [removeAt(int index)](#removeAt-int-) | Menghapus bagian custom xml pada indeks yang ditentukan. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Menghapus kemunculan pertama objek tertentu dari koleksi. |
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
| index | int | Indeks berbasis nol dari elemen yang ingin diambil. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Elemen pada indeks yang ditentukan.

### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah bagian custom xml dalam koleksi. int hanya-baca.

**Mengembalikan:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Menambahkan bagian custom xml baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlString | java.lang.String | String xml dari bagian baru yang akan ditambahkan. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Bagian custom xml yang dibuat.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Menambahkan bagian custom xml baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlData | byte[] | Data xml dari bagian baru yang akan ditambahkan. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Bagian custom xml yang dibuat.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Menambahkan bagian custom xml baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream yang berisi data xml dari bagian baru yang akan ditambahkan. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Bagian custom xml yang dibuat.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus bagian custom xml pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang ingin dihapus. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Menghapus kemunculan pertama objek tertentu dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Bagian custom xml yang akan dihapus. |

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

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). boolean hanya-baca.

**Mengembalikan:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. java.lang.Object hanya-baca.

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

Mengembalikan objek Parent_Immediate. com.aspose.slides.IDOMObject hanya-baca.

**Mengembalikan:**
com.aspose.slides.IDOMObject