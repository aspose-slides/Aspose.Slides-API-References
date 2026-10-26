---
title: ISmartArtNodeCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi node SmartArt.
type: docs
url: /id/com.aspose.slides/ismartartnodecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Mewakili koleksi node SmartArt.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan node berdasarkan indeks. |
| [addNode()](#addNode--) | Menambahkan node baru atau sub node. |
| [removeNode(int index)](#removeNode-int-) | Menghapus node atau sub node berdasarkan indeks. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Menghapus node atau sub node. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Menambahkan node baru pada posisi yang dipilih dalam koleksi node. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Mengembalikan node berdasarkan indeks. Hanya-baca [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen. |

**Mengembalikan:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Menambahkan node baru atau sub node.

**Mengembalikan:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Node yang ditambahkan
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Menghapus node atau sub node berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari node |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Menghapus node atau sub node.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Node yang akan dihapus. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Menambahkan node baru pada posisi yang dipilih dalam koleksi node.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | int | Posisi node berbasis nol. |

**Mengembalikan:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Node yang ditambahkan