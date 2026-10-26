---
title: SequenceCollection
second_title: Aspose.Slides for Android Java API Referansı
description: Etkileşimli sıraların koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/sequencecollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Etkileşimli sıraların koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Bir koleksiyondaki öğe sayısını döndürür. Salt okunur int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Yeni etkileşimli bir sıralama ekler. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Belirtilen sıralamayı bir koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki sıralamayı kaldırır. |
| [clear()](#clear--) | Bir koleksiyondaki tüm sıralamaları kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki bir sıralamayı döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### getCount() {#getCount--}
```
public final int getCount()
```


Bir koleksiyondaki öğe sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Yeni etkileşimli bir sıralama ekler. Okunur/Yazılabilir [Sequence](../../com.aspose.slides/sequence).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Belirtilen sıralamayı bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Kaldırılacak dizi. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Belirtilen indeksteki sıralamayı kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken sıralamanın indeksi. |

### clear() {#clear--}
```
public final void clear()
```


Bir koleksiyondaki tüm sıralamaları kaldırır.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Belirtilen indeksteki bir sıralamayı döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Öğenin indeksi. |

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) nesnesi.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Tüm koleksiyon için bir java.util.Iterator.