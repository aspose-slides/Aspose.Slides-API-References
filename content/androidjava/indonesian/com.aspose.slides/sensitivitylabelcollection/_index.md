---
title: SensitivityLabelCollection
second_title: Referensi API Aspose.Slides untuk Android via Java
description: Mewakili koleksi label sensitivitas yang diterapkan pada dokumen.
type: docs
url: /id/com.aspose.slides/sensitivitylabelcollection/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Mewakili koleksi label sensitivitas yang diterapkan pada dokumen.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan label sensitivitas berdasarkan indeks. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Menambahkan label sensitivitas di akhir koleksi. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Menambahkan SensitivityLabel ke dalam koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus label sensitivitas pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [getCount()](#getCount--) | Mengembalikan jumlah elemen dalam koleksi. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Mengembalikan label sensitivitas berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Menambahkan label sensitivitas di akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | java.lang.String | Id label sensitivitas. |
| siteId | java.util.UUID | Pengidentifikasi situs Azure Active Directory (Azure AD). |
| isEnabled | boolean | Bendera yang menunjukkan apakah label sensitivitas diaktifkan. |
| methodType | int | Metode penugasan untuk label sensitivitas. |

**Mengembalikan:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Menambahkan SensitivityLabel ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Objek SensitivityLabel yang akan ditambahkan di akhir koleksi. |

**Mengembalikan:**
int - Indeks tempat SensitivityLabel ditambahkan.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus label sensitivitas pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks label sensitivitas yang harus dihapus. |

### clear() {#clear--}
```
public final void clear()
```


Menghapus semua elemen dari koleksi.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Sebuah System.Collections.Generic.IEnumerator1 yang dapat digunakan untuk mengiterasi koleksi.
### getCount() {#getCount--}
```
public final int getCount()
```


Mengembalikan jumlah elemen dalam koleksi. Hanya-baca  int .

**Mengembalikan:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Array target. |
| index | int | Indeks awal dalam array target. |