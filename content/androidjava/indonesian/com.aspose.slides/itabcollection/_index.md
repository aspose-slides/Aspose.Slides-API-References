---
title: ITabCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi tab.
type: docs
url: /id/com.aspose.slides/itabcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Mewakili kumpulan tab.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [add(double position, int align)](#add-double-int-) | Menambahkan Tab ke koleksi. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Menambahkan Tab ke koleksi. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [ITab](../../com.aspose.slides/itab).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Menambahkan Tab ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | double | Posisi Tab. |
| align | int | Perataan Tab. |

**Mengembalikan:**
[ITab](../../com.aspose.slides/itab) - Tab yang ditambahkan.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Menambahkan Tab ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Objek Tab yang akan ditambahkan di akhir koleksi. |

**Mengembalikan:**
int - Indeks tempat tab ditambahkan.
### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua elemen dari koleksi.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus elemen pada indeks yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |