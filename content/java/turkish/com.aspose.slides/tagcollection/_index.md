---
title: TagCollection
second_title: Aspose.Slides for Java API Referansı
description: Kullanıcı tanımlı dize çiftlerinden oluşan etiket koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/tagcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Etiket koleksiyonunu temsil eder (kullanıcı tanımlı dize çiftleri)

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
| [remove(String name)](#remove-java.lang.String-) | Koleksiyondan belirtilen ada sahip etiketi kaldırır. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Koleksiyondaki belirtilen anahtarın sıfır tabanlı indeksini döndürür. |
| [contains(String name)](#contains-java.lang.String-) | Koleksiyonun belirli bir adı içerip içermediğini belirler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki etiketi kaldırır. |
| [clear()](#clear--) | Koleksiyondan tüm etiketleri kaldırır. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Belirtilen indeksdeki etiketin değerini döndürür. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Belirtilen indeksdeki etiketin anahtarını döndürür. |
| [getNamesOfTags()](#getNamesOfTags--) | Etiketlerin adlarını döndürür. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondan tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (eşzamanlı) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iteratorü döndürür. |
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
int - Eklenen etiketin indeksi.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Koleksiyondan belirtilen ada sahip etiketi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak etiketin adı. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Koleksiyondaki belirtilen anahtarın sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Koleksiyonda bulunacak ad. |

**Döndürür:**
int - Anahtarın sıfır tabanlı indeksi, bulunamazsa -1.
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

Belirtilen indeksdeki etiketi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak etiketin sıfır tabanlı indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondan tüm etiketleri kaldırır.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Belirtilen indeksdeki etiketin değerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek etiketin indeksi. |

**Döndürür:**
java.lang.String - Etiketin değeri.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Belirtilen indeksdeki etiketin anahtarını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek etiketin indeksi. |

**Döndürür:**
java.lang.String - Etiketin anahtarı.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Etiketlerin adlarını döndürür.

**Döndürür:**
java.lang.String[] - Etiketlerin adları.
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

Koleksiyondan tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doldurulacak dizi. |
| index | int | Hedef dizideki başlangıç konumu. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (eşzamanlı) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Koleksiyon içinde yineleme yapılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Tüm koleksiyon için bir java iteratorü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Tüm koleksiyon için bir java.util.Iterator.