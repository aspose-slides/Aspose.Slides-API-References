---
title: BehaviorCollection
second_title: Aspose.Slides için Java API Referansı
description: Davranış etkilerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/behaviorcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Davranış etkilerinin bir koleksiyonunu temsil eder.
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Bir koleksiyondaki davranışların sayısını döndürür. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt okunur olup olmadığını gösteren bir değer alır. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Koleksiyona yeni bir davranış ekler. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Listede belirli bir öğenin indeksini belirler. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Belirtilen indekste koleksiyona yeni bir davranış ekler. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerinin elemanlarını belirli bir dizi indeksinden başlayarak bir diziye kopyalar. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Koleksiyondan belirtilen davranışı kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indekste koleksiyondan davranışı kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm davranışları kaldırır. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in belirli bir değeri içerip içermediğini belirler. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indekste bir davranış döndürür. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Belirtilen indekste bir davranışı ayarlar. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### getCount() {#getCount--}
```
public final int getCount()
```

Bir koleksiyondaki davranış sayısını döndürür. Salt-okunur int.

**Döndürür:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt okunur olup olmadığını gösteren bir değer alır. Salt-okunur boolean.

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt okunur olması durumunda true; aksi takdirde false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Koleksiyona yeni bir davranış ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eklenecek davranış. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Listede belirli bir öğenin indeksini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Listede bulunacak nesne. |

**Döndürür:**
int - öğe listede bulunursa indeks; aksi takdirde -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Belirtilen indekste koleksiyona yeni bir davranış ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni davranışın eklenmesi gereken indeks. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eklenmek istenen davranış. |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerinin elemanlarını belirli bir dizi indeksinden başlayarak bir diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Öğeleri [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kopyalanan, tek boyutlu dizi. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizi içindeki sıfır tabanlı indeks. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Koleksiyondan belirtilen davranışı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Kaldırılacak davranış. |

**Döndürür:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen indekste koleksiyondan davranışı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak davranışın indeksi. |
### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm davranışları kaldırır.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in belirli bir değeri içerip içermediğini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak nesne. |

**Döndürür:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Belirtilen indekste bir davranış döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek davranışın indeksi. |

**Döndürür:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animasyon davranışı.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Belirtilen indekste bir davranışı ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ayarlanacak davranışın indeksi. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Tüm koleksiyon için bir java.util.Iterator.