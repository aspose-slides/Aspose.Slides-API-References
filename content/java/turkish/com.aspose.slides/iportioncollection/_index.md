---
title: IPortionCollection
second_title: Aspose.Slides for Java API Referansı
description: Bir bölüm koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/iportioncollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Bir bölüm koleksiyonunu temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Bir Portion öğesini koleksiyonun sonuna ekler. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Koleksiyonda belirli bir Portion öğesinin indeksini belirler. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Belirtilen indekste bir Portion öğesini koleksiyona ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içindeki belirli bir nesnenin ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Belirtilen indeksteki öğeyi alır.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Yalnızca okunur int.

**Returns:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Bir Portion öğesini koleksiyonun sonuna ekler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Koleksiyonun sonuna eklenecek Portion. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Koleksiyonda belirli bir Portion öğesinin indeksini belirler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Koleksiyonda bulunacak Portion. |

**Returns:**
int - Koleksiyon içinde bulunursa öğenin indeksi; aksi takdirde -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Belirtilen indekste bir Portion öğesini koleksiyona ekler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Portion öğesinin ekleneceği sıfır tabanlı indeks. |
| value | [IPortion](../../com.aspose.slides/iportion) | Eklenecek Portion. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak nesne. |

**Returns:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) içinden belirli bir nesnenin ilk oluşumunu kaldırır.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde kaldırılacak nesne. |

**Returns:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinden başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca öğe orijinal [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunamazsa false döndürür.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Koleksiyondaki belirtilen indeksteki öğeyi kaldırır.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |