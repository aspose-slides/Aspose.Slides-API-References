---
title: ControlCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Koleksi kontrol ActiveX.
type: docs
url: /id/com.aspose.slides/controlcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Koleksi kontrol ActiveX.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan sejumlah objek dalam koleksi. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Membuat dan menambahkan kontrol baru ke dalam koleksi. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Menghapus kontrol ActiveX dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus kontrol ActiveX yang disimpan pada posisi tertentu dari koleksi. |
| [clear()](#clear--) | Menghapus semua kontrol dari koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan kontrol pada posisi yang ditentukan. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin seluruh koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Mengembalikan sejumlah objek dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```


Membuat dan menambahkan kontrol baru ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| controlType | int | Jenis kontrol yang akan ditambahkan. |
| x | float | Koordinat X untuk sisi kiri bingkai bentuk. |
| y | float | Koordinat Y untuk sisi atas bingkai bentuk. |
| width | float | Lebar bingkai bentuk. |
| height | float | Tinggi bingkai bentuk. |

**Mengembalikan:**
[IControl](../../com.aspose.slides/icontrol) - Kontrol yang dibuat.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```


Menghapus kontrol ActiveX dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Kontrol yang akan dihapus. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus kontrol ActiveX yang disimpan pada posisi tertentu dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kontrol yang akan dihapus. |

### clear() {#clear--}
```
public final void clear()
```


Menghapus semua kontrol dari koleksi.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```


Mengembalikan kontrol pada posisi yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kontrol. |

**Mengembalikan:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin seluruh koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array tujuan |
| index | int | Indeks dalam array tujuan. |

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
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject