---
title: IVbaModuleCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi modul VBA Project.
type: docs
url: /id/com.aspose.slides/ivbamodulecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Mewakili koleksi modul VBA Project.
## Metode

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Menambahkan modul kosong baru ke VBA Project. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Menghapus kemunculan pertama dari objek tertentu dalam koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan.

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

Menambahkan modul kosong baru ke VBA Project.

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

Menghapus kemunculan pertama dari objek tertentu dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Modul yang akan dihapus dari koleksi. |