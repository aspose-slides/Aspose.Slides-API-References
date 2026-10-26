---
title: IBehaviorCollection
second_title: Aspose.Slides için Java API Referansı
description: Davranış efektlerinin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ibehaviorcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Davranış efektlerinin koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki bir davranışı döndürür. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Belirtilen indeksteki bir davranışı döndürür. |
| [getCount()](#getCount--) | Koleksiyondaki davranış sayısını döndürür. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Koleksiyona yeni bir davranış ekler. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Listede belirli bir öğenin indeksini belirler. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Belirtilen indekste koleksiyona yeni bir davranış ekler. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Koleksiyondan belirtilen davranışı kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki davranışı koleksiyondan kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm davranışları kaldırır. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Belirli bir değerin [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde olup olmadığını belirler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Belirtilen indeksteki bir davranışı döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek davranışın indeksi. |

**Döndürür:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animasyon davranışı.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Belirtilen indeksteki bir davranışı döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek davranışın indeksi. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyondaki davranış sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Koleksiyona yeni bir davranış ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eklenecek davranış. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Listede belirli bir öğenin indeksini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Listede bulunacak nesne. |

**Döndürür:**
int - Öğe listede bulunursa indeks; aksi takdirde -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Belirtilen indekste koleksiyona yeni bir davranış ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni davranışın ekleneceği indeks. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eklenecek davranış. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Koleksiyondan belirtilen davranışı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Kaldırılacak davranış. |

**Döndürür:**
boolean - Bir davranış başarıyla kaldırıldıysa true, aksi takdirde false
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indeksteki davranışı koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak davranışın indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm davranışları kaldırır.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Belirli bir değerin [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak nesne. |

**Döndürür:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false