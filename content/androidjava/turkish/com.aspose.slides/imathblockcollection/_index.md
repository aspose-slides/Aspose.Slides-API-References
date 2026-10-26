---
title: IMathBlockCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: IMathBlock matematik blokları koleksiyonu
type: docs
url: /tr/com.aspose.slides/imathblockcollection/
---
**Uygulanan Tüm Arayüzler:**
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

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Koleksiyonun sonuna IMathBlock ekler. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Belirtilen indeksteki IMathBlock'ı koleksiyona ekler. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonun belirtilen indeksindeki öğeyi kaldırır. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Koleksiyondaki belirli bir IMathBlock'un indeksini belirler. |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan eleman sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Belirtilen indeksteki öğeyi alır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

IMathBlock'u koleksiyonun sonuna ekler.

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

Belirtilen indeksteki IMathBlock'ı koleksiyona ekler.

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
| index | int | Öğenin ekleneceği sıfır-tabanlı indeks. |
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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyondan kaldırılacak nesne. |

**Dönen Değer:**
boolean - öğe koleksiyondan başarıyla kaldırıldıysa true; aksi takdirde false. Öğe orijinal koleksiyonda bulunamazsa da false döner.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyonun belirtilen indeksindeki öğeyi kaldırır.

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
| index | int | Kaldırılacak öğenin sıfır-tabanlı indeksi. |

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyonda aranacak nesne. |

**Dönen Değer:**
boolean - öğe koleksiyonda bulunursa true; aksi takdirde false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Koleksiyondaki belirli bir IMathBlock'un indeksini belirler.

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Koleksiyonda aranacak öğe. |

**Dönen Değer:**
int - öğe bulunduysa indeksi; aksi takdirde -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyonda gerçekte bulunan eleman sayısını alır. Yalnızca okunabilir int.

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

Belirtilen indeksteki öğeyi alır. Yalnızca okunabilir [IMathBlock](../../com.aspose.slides/imathblock).

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
| index | int | Alınacak öğenin sıfır-tabanlı indeksi. |

**Dönen Değer:**
[IMathBlock](../../com.aspose.slides/imathblock) - bir matematik metni bloğu.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Belirtilen indeksteki öğeyi alır. Yalnızca okunabilir [IMathBlock](../../com.aspose.slides/imathblock).

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
| index | int | Ayarlanacak öğenin sıfır-tabanlı indeksi. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Bir matematik metni bloğu.

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