---
title: IMathBlockCollection
second_title: Aspose.Slides Java API Referansı
description: Matematik blokları IMathBlock koleksiyonu
type: docs
url: /tr/com.aspose.slides/imathblockcollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Matematik bloklarının koleksiyonu (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```

## Yöntemler

| Method | Description |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Koleksiyonun sonuna IMathBlock ekler. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | IMathBlock'ı belirtilen dizine koleksiyona ekler. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen dizindeki öğeyi kaldırır. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Koleksiyonda belirli bir IMathBlock'ün indeksini belirler. |
| [getCount()](#getCount--) | Koleksiyonun gerçekten içerdiği eleman sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Belirtilen dizindeki öğeyi alır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```


Koleksiyonun sonuna IMathBlock ekler.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyonun sonuna eklenecek bir matematik bloğu |
### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```


IMathBlock'ı belirtilen dizine koleksiyona ekler.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin eklenmesi gereken sıfır tabanlı indeks. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Eklenecek IMathBlock. |
### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```


Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Kaldırılacak nesne. |

**Dönen Değer:**
boolean - öğe koleksiyondan başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca öğe orijinal koleksiyonda bulunamazsa false döner.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Koleksiyonda belirtilen dizindeki öğeyi kaldırır.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |
### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```


Koleksiyonun belirli bir değeri içerip içermediğini belirler.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyonda bulunacak nesne. |

**Dönen Değer:**
boolean - öğe koleksiyonda bulunursa true; aksi takdirde false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```


Koleksiyonda belirli bir IMathBlock'ün indeksini belirler.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyonda bulunacak öğe. |

**Dönen Değer:**
int - Öğenin koleksiyonda bulunması durumunda indeksi; aksi takdirde -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyonun gerçekten içerdiği eleman sayısını alır. Salt okunur int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Dönen Değer:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```


Belirtilen dizindeki öğeyi alır. Salt okunur [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak öğenin sıfır tabanlı indeksi. |

**Dönen Değer:**
[IMathBlock](../../com.aspose.slides/imathblock) - Matematik metni bloğu.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```


Belirtilen dizindeki öğeyi alır. Salt okunur [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ayarlanacak öğenin sıfır tabanlı indeksi. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Matematik metni bloğu.
### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```