---
title: ISensitivityLabelCollection
second_title: Referensi API Aspose.Slides untuk Android via Java
description: Mewakili kumpulan label sensitivitas yang diterapkan pada dokumen.
type: docs
url: /id/com.aspose.slides/isensitivitylabelcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Mewakili kumpulan label sensitivitas yang diterapkan pada dokumen.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan label sensitivitas berdasarkan indeks. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Menambahkan label sensitivitas di akhir koleksi. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Menambahkan SensitivityLabel ke koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus label sensitivitas pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [getCount()](#getCount--) | Mendapatkan jumlah semua elemen dalam koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Mengembalikan label sensitivitas berdasarkan indeks. Baca-saja [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Menambahkan label sensitivitas di akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | java.lang.String | ID label sensitivitas. |
| siteId | java.util.UUID | Pengidentifikasi situs Azure Active Directory (Azure AD). |
| isEnabled | boolean | Bendera yang menunjukkan apakah label sensitivitas diaktifkan. |
| methodType | int | Metode penugasan untuk label sensitivitas. |

**Mengembalikan:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Menambahkan SensitivityLabel ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Objek SensitivityLabel yang akan ditambahkan di akhir koleksi. |

**Mengembalikan:**
int - Indeks di mana SensitivityLabel ditambahkan.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus label sensitivitas pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks label sensitivitas yang harus dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua elemen dari koleksi.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Mendapatkan jumlah semua elemen dalam koleksi. Baca-saja  int .

**Mengembalikan:**
int