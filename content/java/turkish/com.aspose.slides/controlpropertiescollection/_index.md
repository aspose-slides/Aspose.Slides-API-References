---
title: ControlPropertiesCollection
second_title: Aspose.Slides for Java API Referansı
description: AcitveX özelliklerinin bir koleksiyonu.
type: docs
url: /tr/com.aspose.slides/controlpropertiescollection/
---
**Kalıtım:**  
java.lang.Object

**Tüm Uygulanan Arayüzler:**  
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)  
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

ActiveX özelliklerinin bir koleksiyonu.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Koleksiyona bir özellik ekler. |
| [remove(String name)](#remove-java.lang.String-) | Belirtilen ada sahip bir özelliği kaldırır. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Özelliği geri döndürür veya ayarlar. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Özelliği geri döndürür veya ayarlar. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Özellik adlarının koleksiyonunu geri döndürür. |
| [clear()](#clear--) | Tüm özellikleri kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki özellik sayısını geri döndürür. |
| [iterator()](#iterator--) | Koleksiyon üzerinden yineleme yapan bir enumerator döndürür. |
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

Belirtilen ada sahip bir özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak özelliğin adı. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Özelliği geri döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Özelliğin adı. |

**Dönüş Değeri:**
java.lang.String - Özellik.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Özelliği geri döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Özelliğin adı. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Özellik adlarının koleksiyonunu geri döndürür. Salt okunur [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Dönüş Değeri:**
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

Koleksiyondaki özellik sayısını geri döndürür. Salt okunur int.

**Dönüş Değeri:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Koleksiyon üzerinden yineleme yapan bir enumerator döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Koleksiyon üzerinden yineleme yapmak için kullanılabilen bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Tüm koleksiyon için bir java.util.Iterator.