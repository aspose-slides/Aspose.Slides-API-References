---
title: BehaviorPropertyCollection
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Etki davranışı için zamanlama özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/behaviorpropertycollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Etkileşim davranışı için zamanlama özelliklerini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda depolanan özelliklerin sayısını döndürür. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt-okunur olup olmadığını gösteren bir değer alır. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Koleksiyona yeni bir özellik ekler. |
| [add(String propertyValue)](#add-java.lang.String-) | Koleksiyona yeni bir özellik ekler. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Listede belirli bir öğenin dizinini belirler. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Listede özellik değerine göre belirli bir öğenin dizinini belirler. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Belirtilen dizinde koleksiyona yeni bir özellik ekler. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Belirtilen özellik değerine sahip yeni bir özelliği belirtilen dizinde koleksiyona ekler. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Belirli bir dizi indeksinden başlayarak [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir diziye kopyalar. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Belirtilen özelliği koleksiyondan kaldırır. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Belirtilen özelliği koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki özelliği kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm özellikleri kaldırır. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler. |
| [contains(String propertyValue)](#contains-java.lang.String-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki bir özelliği döndürür. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Belirtilen dizindeki bir özelliği ayarlar. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |

### size() {#size--}
```
public final int size()
```

Koleksiyonda depolanan özelliklerin sayısını döndürür. Salt-okunur int.

**Döndürür:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in salt-okunur olup olmadığını gösteren bir değer alır. Salt-okunur boolean.

**Döndürür:**
boolean - true ise [IGenericCollection](../../com.aspose.slides/igenericcollection) salt-okunur; aksi takdirde false.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Koleksiyona yeni bir özellik ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Eklenecek özellik. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Koleksiyona yeni bir özellik ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Eklenecek özelliğin değeri. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Listede belirli bir öğenin dizinini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Listede bulunacak nesne. |

**Döndürür:**
int - öğe listede bulunursa indeks; aksi takdirde -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Listede özellik değerine göre belirli bir öğenin dizinini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | özelliğin değeri |

**Döndürür:**
int - belirtilen değere sahip özelliğin indeksi

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Belirtilen dizinde koleksiyona yeni bir özellik ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni bir özelliğin eklenmesi gereken indeks. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Eklenecek özellik. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Belirtilen özellik değerine sahip yeni bir özelliği belirtilen dizinde koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni bir özelliğin eklenmesi gereken indeks. |
| propertyValue | java.lang.String | Eklenecek özelliğin değeri. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Kopyalanan öğelerin hedefi olan tek boyutlu dizi. [IGenericCollection](../../com.aspose.slides/igenericcollection)'den öğeler kopyalanır. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başladığı dizi içindeki sıfır tabanlı indeks. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Koleksiyondan belirtilen özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Kaldırılacak özellik. |

**Döndürür:**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Koleksiyondan belirtilen özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Kaldırılacak özelliğin değeri. |

**Döndürür:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen dizindeki özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken özelliğin indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm özellikleri kaldırır.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak özellik. |

**Döndürür:**
boolean - true ise öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunur; aksi takdirde false.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak özelliğin değeri. |

**Döndürür:**
boolean - true ise propertyValue [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunur; aksi takdirde false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Belirtilen dizindeki bir özelliği döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek özelliğin indeksi. |

**Döndürür:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animation behavior property.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Belirtilen dizindeki bir özelliği ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek özelliğin indeksi. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Koleksiyon üzerinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - A IGenericEnumerator that can be used to iterate through the collection.

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Döndürür:**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Döndürür:**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Döndürür:**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - An java.util.Iterator for the entire collection.