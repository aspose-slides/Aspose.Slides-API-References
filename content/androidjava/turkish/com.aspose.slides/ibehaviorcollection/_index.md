---
title: IBehaviorCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Davranış etkileri koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ibehaviorcollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Davranış etkilerinin koleksiyonunu temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki bir davranışı döndürür. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Belirtilen indeksteki bir davranışı döndürür. |
| [getCount()](#getCount--) | Bir koleksiyondaki davranış sayısını döndürür. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Bir koleksiyona yeni davranış ekler. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Listede belirli bir öğenin indeksini belirler. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Belirtilen indekste bir koleksiyona yeni davranış ekler. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Belirtilen davranışı bir koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indekste bir koleksiyondan davranışı kaldırır. |
| [clear()](#clear--) | Bir koleksiyondaki tüm davranışları kaldırır. |
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

**Dönüş Değeri:**
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

Bir koleksiyondaki davranış sayısını döndürür. Salt okunur int.

**Dönüş Değeri:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Bir koleksiyona yeni davranış ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eklemek için davranış. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Listede belirli bir öğenin indeksini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Listede bulunacak nesne. |

**Dönüş Değeri:**
int - Öğenin listede bulunması durumunda indeksi; aksi takdirde -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Belirtilen indekste bir koleksiyona yeni davranış ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni davranışın eklenmesi gereken indeks. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eklenecek davranış. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Belirtilen davranışı bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Kaldırılacak davranış. |

**Dönüş Değeri:**
boolean - Bir davranış başarıyla kaldırıldıysa true
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indekste bir koleksiyondan davranışı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak davranışın indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```

Bir koleksiyondaki tüm davranışları kaldırır.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Belirli bir değerin [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak nesne. |

**Dönüş Değeri:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.