---
title: ITagCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Kullanıcı tanımlı dize çiftlerinden oluşan etiket koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/itagcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Etiketlerin koleksiyonunu temsil eder (kullanıcı tanımlı dize çiftleri)
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Koleksiyona yeni bir etiket ekler. |
| [remove(String name)](#remove-java.lang.String-) | Koleksiyondan belirtilen ada sahip etiketi kaldırır. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Koleksiyondaki belirtilen anahtarın sıfır tabanlı indeksini döndürür. |
| [contains(String name)](#contains-java.lang.String-) | Koleksiyonun belirli bir adı içerip içermediğini belirler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki etiketi kaldırır. |
| [clear()](#clear--) | Koleksiyondan tüm etiketleri kaldırır. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Belirtilen indeksteki bir etiketin değerini döndürür. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Belirtilen indeksteki bir etiketin anahtarını döndürür. |
| [getNamesOfTags()](#getNamesOfTags--) | Etiketlerin adlarını döndürür. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
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
public abstract void remove(String name)
```


Koleksiyondan belirtilen ada sahip etiketi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak etiketin adı. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```


Koleksiyondaki belirtilen anahtarın sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Koleksiyonda bulunacak ad. |

**Döndürür:**
int - Anahtar bulunduysa sıfır tabanlı indeks; aksi takdirde -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```


Koleksiyonun belirli bir adı içerip içermediğini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bulunacak anahtar. |

**Döndürür:**
boolean - Koleksiyon belirtilen anahtara sahip bir etiket içeriyorsa doğru; aksi takdirde yanlış.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indeksteki etiketi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak etiketin sıfır tabanlı indeksi. |
### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondan tüm etiketleri kaldırır.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Belirtilen indeksteki bir etiketin değerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek bir etiketin indeksi. |

**Döndürür:**
java.lang.String - Bir etiketin değeri.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Belirtilen indeksteki bir etiketin anahtarını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek bir etiketin indeksi. |

**Döndürür:**
java.lang.String - Bir etiketin anahtarı.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Etiketlerin adlarını döndürür.

**Döndürür:**
java.lang.String[] - Etiketlerin adları.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bir etiketin anahtarı. |

**Döndürür:**
java.lang.String - Bir etiketin değeri.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Bir etiketin anahtarı. |
| value | java.lang.String |  |