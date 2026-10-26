---
title: SequenceCollection
second_title: Aspose.Slides for Java API Referansı
description: Etkileşimli sekansların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/sequencecollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Etkileşimli sekansların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Bir koleksiyondaki öğelerin sayısını döndürür Yalnızca okunabilir int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Yeni bir etkileşimli sekans ekler. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Belirtilen sekansı bir koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki sekansı kaldırır. |
| [clear()](#clear--) | Bir koleksiyondaki tüm sekansları kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki bir sekansı döndürür. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### getCount() {#getCount--}
```
public final int getCount()
```

Bir koleksiyondaki öğelerin sayısını döndürür Yalnızca okunabilir int.

**Döndürür:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

Yeni bir etkileşimli sekans ekler. Okunabilir/yazılabilir [Sequence](../../com.aspose.slides/sequence).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

Belirtilen sekansı bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Kaldırılacak sekans. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen dizindeki sekansı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken sekansın indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Bir koleksiyondaki tüm sekansları kaldırır.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

Belirtilen dizindeki bir sekansı döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin indeksi. |

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) nesnesi.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

Koleksiyon üzerinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Koleksiyon üzerinde yineleme için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Tüm koleksiyon için bir java.util.Iterator.