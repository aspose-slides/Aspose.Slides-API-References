---
title: IVbaModuleCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Merepresentasikan koleksi modul Proyek VBA.
type: docs
url: /id/com.aspose.slides/ivbamodulecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Merepresentasikan koleksi modul Proyek VBA.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Menambahkan modul kosong baru ke Proyek VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Menghapus kemunculan pertama dari objek tertentu dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Mengambil elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


Menambahkan modul kosong baru ke Proyek VBA.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama modul |

**Mengembalikan:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Modul yang ditambahkan.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Menghapus kemunculan pertama dari objek tertentu dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Modul yang akan dihapus dari koleksi. |