---
title: TextAnimationCollection
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili koleksi animasi teks.
type: docs
url: /id/com.aspose.slides/textanimationcollection/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Mewakili koleksi animasi teks.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan sejumlah elemen dalam koleksi. |
| [add()](#add--) | Menambahkan animasi teks baru ke koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan elemen berdasarkan indeks. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Mengembalikan semua elemen |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke dalam array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |

### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```

### size() {#size--}
```
public final int size()
```

Mengembalikan sejumlah elemen dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int

### add() {#add--}
```
public final TextAnimation add()
```

Menambahkan animasi teks baru ke koleksi.

**Mengembalikan:**
[TextAnimation](../../com.aspose.slides/textanimation) - Ditambahkan [TextAnimation](../../com.aspose.slides/textanimation)

### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

Mengembalikan elemen berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

Mengembalikan semua elemen

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) untuk dihapus. |

**Mengembalikan:**
com.aspose.slides.ITextAnimation[] - Array dari [ITextAnimation](../../com.aspose.slides/itextanimation)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Sebuah java.util.Iterator untuk seluruh koleksi.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke dalam array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array yang akan diisi. |
| index | int | Posisi mulai dalam array target. |

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