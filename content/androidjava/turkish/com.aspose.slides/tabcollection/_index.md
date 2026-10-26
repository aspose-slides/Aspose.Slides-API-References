---
title: TabCollection
second_title: Android için Aspose.Slides Java API Referansı
description: Sekmelerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/tabcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Sekmelerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan eleman sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [add(double position, int align)](#add-double-int-) | Koleksiyona bir Sekme ekler. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Koleksiyona bir Sekme ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | İki TabsEx örneğinin eşit olup olmadığını belirler. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratör döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iteratörü döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```


Koleksiyonda gerçekte bulunan eleman sayısını alır. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Salt okunur [Tab](../../com.aspose.slides/tab).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


Koleksiyona bir Sekme ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Döndürür:**
[ITab](../../com.aspose.slides/itab) - Eklenmiş sekme.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


Koleksiyona bir Sekme ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Koleksiyonun sonuna eklenecek Tab nesnesi. |

**Döndürür:**
int - Sekmenin eklendiği indeks.
### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Koleksiyonda belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki TabsEx örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Mevcut TabsEx ile karşılaştırılacak TabsEx. |

**Döndürür:**
boolean - **true** eğer belirtilen TabsEx mevcut TabsEx ile eşitse; aksi takdirde **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Koleksiyon içinde yineleme yapan bir enumeratör döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Tüm koleksiyon için bir java iteratörü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object