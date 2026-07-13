---
title: SmartArtNodeCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi node SmartArt.
type: docs
url: /id/com.aspose.slides/smartartnodecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Mewakili koleksi node SmartArt.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan node berdasarkan indeks |
| [size()](#size--) | Mengembalikan jumlah node dalam koleksi Baca-saja  int  Baca-saja  int . |
| [addNode()](#addNode--) | Menambahkan node SmartArt baru atau sub node. |
| [removeNode(int index)](#removeNode-int-) | Menghapus node atau sub node berdasarkan indeks |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Menghapus node atau sub node |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Menambahkan node baru pada posisi terpilih dalam koleksi node |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan root sinkronisasi. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


Mengembalikan node berdasarkan indeks

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen yang dimulai dari nol |

**Mengembalikan:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Node SmartArt
### size() {#size--}
```
public final int size()
```


Mengembalikan jumlah node dalam koleksi Baca-saja  int  Baca-saja  int .

**Mengembalikan:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


Menambahkan node SmartArt baru atau sub node.

**Mengembalikan:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Node yang ditambahkan
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


Menghapus node atau sub node berdasarkan indeks

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks node yang dimulai dari nol |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


Menghapus node atau sub node

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Node yang dihapus |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


Menambahkan node baru pada posisi terpilih dalam koleksi node

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | int | Posisi node yang dimulai dari nol |

**Mengembalikan:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Node yang ditambahkan
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). Baca-saja  boolean .

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Mengembalikan root sinkronisasi. Baca-saja Object.

**Mengembalikan:**
java.lang.Object