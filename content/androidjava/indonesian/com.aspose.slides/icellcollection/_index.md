---
title: ICellCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi sel.
type: docs
url: /id/com.aspose.slides/icellcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Mewakili koleksi sel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan sel berdasarkan posisinya. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Mengembalikan sel berdasarkan posisinya. Hanya-baca [ICell](../../com.aspose.slides/icell).

--------------------

Satu objek CellEx dapat dikembalikan untuk beberapa indeks bila sel digabung.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ICell](../../com.aspose.slides/icell)