---
title: PortionCollection
second_title: Java API Referansı ile Android için Aspose.Slides
description: Bölümlerden oluşan bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/portioncollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Bölümlerden oluşan bir koleksiyonu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) nin salt-okunur olup olmadığını gösteren bir değeri alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Belirtilen dizindeki öğeyi alır. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Bir Portion'ı koleksiyonun sonuna ekler. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | List içinde belirli bir öğenin dizinini belirler. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Belirtilen dizinde Portion'ı koleksiyona ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) nin belirli bir değeri içerip içermediğini belirler. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir Dizi'ye, belirli bir Dizi dizininde başlayarak kopyalar. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Belirli bir nesnenin [IGenericCollection](../../com.aspose.slides/igenericcollection) içindeki ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonun belirtilen dizindeki öğesini kaldırır. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### getCount() {#getCount--}
```
public final int getCount()
```


Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Salt-okunur int.

**Döndürür:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) nin salt-okunur olup olmadığını gösteren bir değeri alır. Salt-okunur boolean.

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) salt-okunur ise true; aksi takdirde false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Belirtilen dizindeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```


Belirtilen dizindeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Bir Portion'ı koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Koleksiyonun sonuna eklenecek Portion. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


List içinde belirli bir öğenin dizinini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | List içinde bulunacak nesne. |

**Döndürür:**
int - öğe listede bulunursa dizini; aksi takdirde -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```


Belirtilen dizinde Portion'ı koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Portion'ın ekleneceği sıfır tabanlı dizin. |
| value | [IPortion](../../com.aspose.slides/iportion) | Eklenecek Portion. |

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) nin belirli bir değeri içerip içermediğini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak nesne. |

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde öğe bulunursa true; aksi takdirde false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir Dizi'ye, belirli bir Dizi dizininde başlayarak kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerinden kopyalanan elemanların hedefi olan tek boyutlu Dizi. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizideki sıfır tabanlı indeks. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) içindeki belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinden kaldırılacak nesne. |

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde öğe başarıyla kaldırıldıysa true; aksi takdirde false. Bu metod ayrıca öğe orijinal [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunamazsa false döndürür.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Koleksiyonun belirtilen dizindeki öğesini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı dizini. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Koleksiyon üzerinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Koleksiyon üzerinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Tüm koleksiyon için bir java.util.Iterator.