---
title: IMathBlockCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Koleksi blok matematika IMathBlock
type: docs
url: /id/com.aspose.slides/imathblockcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Koleksi blok matematika (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Menambahkan IMathBlock ke akhir koleksi. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Menyisipkan IMathBlock ke dalam koleksi pada indeks yang ditentukan. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Menghapus kemunculan pertama dari objek tertentu dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus sebuah item pada indeks yang ditentukan dalam koleksi. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Menentukan apakah koleksi berisi nilai tertentu. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Menentukan indeks dari IMathBlock tertentu dalam koleksi. |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan item pada indeks yang ditentukan. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Mendapatkan item pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Menambahkan IMathBlock ke akhir koleksi.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Blok matematika yang akan ditambahkan ke akhir koleksi |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Menyisipkan IMathBlock ke dalam koleksi pada indeks yang ditentukan.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol tempat item harus disisipkan. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock yang akan disisipkan. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Menghapus kemunculan pertama dari objek tertentu dari koleksi.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objek yang akan dihapus dari koleksi. |

**Mengembalikan:**
boolean - true jika item berhasil dihapus dari koleksi; jika tidak, false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam koleksi asli.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus sebuah item pada indeks yang ditentukan dalam koleksi.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari item yang akan dihapus. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Menentukan apakah koleksi berisi nilai tertentu.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objek yang akan dicari dalam koleksi. |

**Mengembalikan:**
boolean - true jika item ditemukan dalam koleksi; jika tidak, false.

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Menentukan indeks dari IMathBlock tertentu dalam koleksi.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Item yang akan dicari dalam koleksi. |

**Mengembalikan:**
int - Indeks item jika ditemukan dalam koleksi; jika tidak, -1.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. Hanya-baca int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Mengembalikan:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Mendapatkan item pada indeks yang ditentukan. Hanya-baca [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari item yang akan diambil. |

**Mengembalikan:**
[IMathBlock](../../com.aspose.slides/imathblock) - Blok teks matematika.

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Mendapatkan item pada indeks yang ditentukan. Hanya-baca [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari item yang akan diatur. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Blok teks matematika. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua elemen dari koleksi.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```