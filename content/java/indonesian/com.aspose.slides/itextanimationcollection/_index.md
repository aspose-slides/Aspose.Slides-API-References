---
title: ITextAnimationCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi animasi teks.
type: docs
url: /id/com.aspose.slides/itextanimationcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Mewakili koleksi animasi teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan elemen dengan indeks. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Mengembalikan semua elemen |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Mengembalikan elemen dengan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Mengembalikan semua elemen

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) elemen. |

**Mengembalikan:**
com.aspose.slides.ITextAnimation[] - Array dari [ITextAnimation](../../com.aspose.slides/itextanimation)