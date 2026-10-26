---
title: ICustomXmlPartCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi bagian xml khusus.
type: docs
url: /id/com.aspose.slides/icustomxmlpartcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Mewakili koleksi bagian xml khusus.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan elemen pada indeks yang ditentukan. |
| [add(byte[] xmlData)](#add-byte---) | Menambahkan bagian xml khusus baru. |
| [add(String xmlString)](#add-java.lang.String-) | Menambahkan bagian xml khusus baru. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Menambahkan bagian xml khusus baru. |
| [removeAt(int index)](#removeAt-int-) | Menghapus bagian xml khusus pada indeks yang ditentukan. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Menghapus kemunculan pertama dari objek tertentu dalam koleksi. |
| [clear()](#clear--) | Menghapus semua item dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Mengembalikan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan diambil. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Elemen pada indeks yang ditentukan.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Menambahkan bagian xml khusus baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlData | byte[] | Data xml dari bagian baru yang akan ditambahkan. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Bagian xml khusus yang dibuat.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Menambahkan bagian xml khusus baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlString | java.lang.String | String xml dari bagian baru yang akan ditambahkan. |

**Mengembalikan:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Bagian xml khusus yang dibuat.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
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
public abstract void removeAt(int index)
```

Menghapus bagian xml khusus pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
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
public abstract void clear()
```

Menghapus semua item dari koleksi.