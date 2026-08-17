---
title: ITagCollection
second_title: Aspose.Slides için Java API Referansı
description: Etiketlerin (kullanıcı tanımlı dize çiftleri) koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/itagcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Etiketlerin (kullanıcı tanımlı dize çiftleri) koleksiyonunu temsil eder
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Koleksiyona yeni bir etiket ekler. |
| [remove(String name)](#remove-java.lang.String-) | Koleksiyondan belirtilen ada sahip etiketi kaldırır. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Koleksiyonda belirtilen anahtarın sıfırdan başlayan indeksini döndürür. |
| [contains(String name)](#contains-java.lang.String-) | Koleksiyonun belirli bir adı içerip içermediğini belirler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki etiketi kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm etiketleri kaldırır. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Belirtilen indeksteki etiketin değerini döndürür. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Belirtilen indeksteki etiketin anahtarını döndürür. |
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

Koleksiyonda belirtilen anahtarın sıfırdan başlayan indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Koleksiyonda aranacak ad. |

**Döndürür:**
int - Eğer anahtar koleksiyonda bulunursa anahtarın sıfırdan başlayan indeksi; aksi takdirde -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Koleksiyonun belirli bir adı içerip içermediğini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Aranacak anahtar. |

**Döndürür:**
boolean - Belirtilen anahtara sahip bir etiket koleksiyonda varsa true; aksi takdirde false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indeksteki etiketi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak etiketin sıfırdan başlayan indeksi. |
### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm etiketleri kaldırır.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Belirtilen indeksteki etiketin değerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek etiketin indeksi. |

**Döndürür:**
java.lang.String - Etiketin değeri.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Belirtilen indeksteki etiketin anahtarını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Döndürülecek etiketin indeksi. |

**Döndürür:**
java.lang.String - Etiketin anahtarı.
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
| name | java.lang.String | Etiketin anahtarı. |

**Döndürür:**
java.lang.String - Etiketin değeri.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Bir etiketin anahtar ve değer çiftini döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Etiketin anahtarı. |
| value | java.lang.String |  |
