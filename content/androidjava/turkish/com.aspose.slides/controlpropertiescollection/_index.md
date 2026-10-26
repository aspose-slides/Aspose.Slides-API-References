---
title: ControlPropertiesCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: AcitveX özelliklerinin bir koleksiyonu.
type: docs
url: /tr/com.aspose.slides/controlpropertiescollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

AcitveX özelliklerinin bir koleksiyonu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Koleksiyona bir özellik ekler. |
| [remove(String name)](#remove-java.lang.String-) | Belirtilen isimle bir özelliği kaldırır. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Özelliği döndürür veya ayarlar. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Özelliği döndürür veya ayarlar. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Özellik adlarının koleksiyonunu döndürür. |
| [clear()](#clear--) | Tüm özellikleri kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki özellik sayısını döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Koleksiyona bir özellik ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Özelliğin adı. |
| value | java.lang.String | Özelliğin değeri. |
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Belirtilen isimle bir özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak özelliğin adı. |
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Özelliği döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Özellik adı. |

**Döndürür:**
java.lang.String - Özellik.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Özelliği döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Özellik adı. |
| value | java.lang.String |  |
### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Özellik adlarının koleksiyonunu döndürür. Yalnızca okunabilir [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Döndürür:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

Tüm özellikleri kaldırır.
### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyondaki özellik sayısını döndürür. Yalnızca okunabilir int.

**Döndürür:**
int
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