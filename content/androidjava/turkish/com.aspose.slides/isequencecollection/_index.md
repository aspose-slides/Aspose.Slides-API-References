---
title: ISequenceCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Etkileşimli dizilerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/isequencecollection/
---
**Tüm Gerçekleştirilen Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Etkileşimli dizilerin bir koleksiyonunu temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Bir koleksiyondaki öğelerin sayısını döndürür Salt Okunur int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Yeni etkileşimli bir dizi ekler. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Belirtilen diziyi bir koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki diziyi kaldırır. |
| [clear()](#clear--) | Bir koleksiyondaki tüm dizileri kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki bir dizi döndürür. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Bir koleksiyondaki öğelerin sayısını döndürür Salt Okunur int.

**Döndürür:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Yeni etkileşimli bir dizi ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Şekil nesnesi [IShape](../../com.aspose.slides/ishape) |

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence) - Yeni dizi [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Belirtilen diziyi bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Kaldırılacak dizi. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indeksteki diziyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Koleksiyondaki öğenin indeksi int |

### clear() {#clear--}
```
public abstract void clear()
```

Bir koleksiyondan tüm dizileri kaldırır.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Belirtilen indeksteki bir diziyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin indeksi. |

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) nesnesi.