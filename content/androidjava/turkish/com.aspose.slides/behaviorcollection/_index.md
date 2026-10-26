---
title: BehaviorCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Davranış etkilerinin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/behaviorcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Davranış etkilerinin koleksiyonunu temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyondaki davranışların sayısını döndürür. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okuma olup olmadığını gösteren bir değer alır. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Yeni bir davranışı koleksiyona ekler. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Listede belirli bir öğenin dizinini belirler. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Yeni bir davranışı belirtilen dizinde koleksiyona ekler. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in elemanlarını bir diziye, belirli bir dizi indeksinden başlayarak kopyalar. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Belirtilen davranışı koleksiyonundan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizinde koleksiyondan davranışı kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm davranışları kaldırır. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in belirli bir değeri içerip içermediğini belirler. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki bir davranışı döndürür. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Belirtilen dizinde bir davranışı ayarlar. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |

### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyondaki davranışların sayısını döndürür. Yalnızca okuma int.

**Döndürür:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okuma olup olmadığını gösteren bir değer alır. Yalnızca okuma boolean.

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okuma olması durumunda true; aksi takdirde false.

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Yeni bir davranışı koleksiyona ekler.

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
int - Öğe listede bulunursa indeks; aksi takdirde -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Belirtilen dizinde koleksiyona yeni bir davranış ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni davranışın eklenmesi gereken dizin. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eklenecek davranış. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in elemanlarını bir diziye, belirli bir dizi indeksinden başlayarak kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kopyalanan elemanların hedefi olan tek boyutlu dizi. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizideki sıfır tabanlı indeks. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Belirtilen davranışı bir koleksiyondan kaldırır.

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

Belirtilen dizinde koleksiyondan davranışı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak davranışın dizini. |

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

Belirtilen dizindeki bir davranışı döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek davranışın dizini. |

**Döndürür:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animasyon davranışı.

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Belirtilen dizinde bir davranışı ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ayarlanacak davranışın dizini. |
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