---
title: BehaviorPropertyCollection
second_title: Aspose.Slides for Java API Referansı
description: Etki davranışı için zamanlama özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/behaviorpropertycollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Etki davranışı için zamanlama özelliklerini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda depolanan özellik sayısını döndürür. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okunabilir olup olmadığını gösteren bir değeri alır. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Koleksiyona yeni bir özellik ekler. |
| [add(String propertyValue)](#add-java.lang.String-) | Koleksiyona yeni bir özellik ekler. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Listede belirli bir öğenin dizinini belirler. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Listede özellik değerine göre belirli bir öğenin dizinini belirler. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Belirtilen dizinde koleksiyona yeni bir özellik ekler. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Belirtilen dizinde koleksiyona yeni bir özellik (belirtilen özellik değeriyle) ekler. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir diziye kopyalar, belirli bir dizi indeksiyle başlar. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Belirtilen özelliği koleksiyondan kaldırır. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Belirtilen özelliği koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki özelliği kaldırır. |
| [clear()](#clear--) | Tüm özellikleri koleksiyondan kaldırır. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler. |
| [contains(String propertyValue)](#contains-java.lang.String-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki bir özelliği döndürür. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Belirtilen dizindeki bir özelliği ayarlar. |
| [iterator()](#iterator--) | Koleksiyonu yineleyen bir yineleyici döndürür. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |

### size() {#size--}
```
public final int size()
```

Koleksiyonda depolanan özellik sayısını döndürür. Yalnızca okunabilir int.

**Döndürür:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okunabilir olup olmadığını gösteren bir değeri alır. Yalnızca okunabilir boolean.

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) yalnızca okunabilir ise true; aksi takdirde false.

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
int - öğe listede bulunursa dizini; bulunmazsa -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Listede özellik değerine göre belirli bir öğenin dizinini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Özelliğin değeri |

**Döndürür:**
int - belirtilen değere sahip özelliğin dizini

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Koleksiyona belirtilen dizinde yeni bir özellik ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni özelliğin ekleneceği dizin. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Eklenecek özellik. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Koleksiyona belirtilen dizinde yeni bir özellik (belirtilen özellik değeriyle) ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni özelliğin ekleneceği dizin. |
| propertyValue | java.lang.String | Eklenecek özelliğin değeri. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir diziye kopyalar, belirli bir dizi indeksiyle başlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'dan kopyalanan öğelerin hedefi olan tek boyutlu dizi. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizi indeksi (sıfır tabanlı). |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Belirtilen özelliği koleksiyondan kaldırır.

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

Belirtilen özelliği koleksiyondan kaldırır.

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
| index | int | Silinecek özelliğin dizini. |

### clear() {#clear--}
```
public final void clear()
```

Tüm özellikleri koleksiyondan kaldırır.

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
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.

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
boolean - propertyValue [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Belirtilen dizindeki bir özelliği döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek özelliğin dizini. |

**Döndürür:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animasyon davranış özelliği.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Belirtilen dizinde bir özelliği ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ayarlanacak özelliğin dizini. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Koleksiyonu yineleyen bir yineleyici döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Koleksiyonu yinelemek için kullanılabilecek bir IGenericEnumerator.

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

Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Tüm koleksiyon için bir java.util.Iterator.