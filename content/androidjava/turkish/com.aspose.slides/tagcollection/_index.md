---
title: TagCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Kullanıcı tanımlı dize çiftlerinden oluşan etiket koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/tagcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Koleksiyonun (kullanıcı tanımlı dize çiftleri) etiketlerini temsil eder

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki etiket sayısını döndürür. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Koleksiyona yeni bir etiket ekler. |
| [remove(String name)](#remove-java.lang.String-) | Belirtilen ada sahip etiketi koleksiyondan kaldırır. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Koleksiyondaki belirtilen anahtarın sıfır tabanlı dizinini döndürür. |
| [contains(String name)](#contains-java.lang.String-) | Koleksiyonun belirli bir adı içerip içermediğini belirler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki etiketi kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm etiketleri kaldırır. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Belirtilen dizindeki etiketin değerini döndürür. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Belirtilen dizindeki etiketiin anahtarını döndürür. |
| [getNamesOfTags()](#getNamesOfTags--) | Etiket adlarını döndürür. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki etiket sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Koleksiyona yeni bir etiket ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Etiketin adı. |
| value | java.lang.String | Etiketin değeri. |

**Döndürür:**
int - Eklenen etiketin dizini.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Belirtilen ada sahip etiketi koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak etiketin adı. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Koleksiyondaki belirtilen anahtarın sıfır tabanlı dizinini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Koleksiyonda bulunacak ad. |

**Döndürür:**
int - Anahtarın sıfır tabanlı dizini, anahtar koleksiyonda bulunursa; aksi takdirde -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Koleksiyonun belirli bir adı içerip içermediğini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bulunacak anahtar. |

**Döndürür:**
boolean - Koleksiyon belirtilen anahtara sahip bir etiket içeriyorsa true; aksi takdirde false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen dizindeki etiketi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak etiketin sıfır tabanlı dizini. |
### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm etiketleri kaldırır.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Belirtilen dizindeki etiketin değerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Dönen etiketin dizini. |

**Döndürür:**
java.lang.String - Etiketin değeri.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Belirtilen dizindeki etiketin anahtarını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Dönen etiketin dizini. |

**Döndürür:**
java.lang.String - Etiketin anahtarı.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Etiket adlarını döndürür.

**Döndürür:**
java.lang.String[] - Etiket adları.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Etiketin anahtarı. |

**Döndürür:**
java.lang.String - Etiketin değeri.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Etiketin anahtarı. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doldurulacak dizi. |
| index | int | Hedef dizide başlangıç konumu. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.