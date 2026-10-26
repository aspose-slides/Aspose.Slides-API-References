---
title: IControlPropertiesCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: ActiveX denetimlerinin bir koleksiyonu.
type: docs
url: /tr/com.aspose.slides/icontrolpropertiescollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX denetimlerinin bir koleksiyonu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyondaki özellik sayısını döndürür. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Koleksiyona bir özellik ekler. |
| [remove(String name)](#remove-java.lang.String-) | Belirtilen ada sahip bir özelliği kaldırır. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Özelliği döndürür veya ayarlar. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Özelliği döndürür veya ayarlar. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Koleksiyondaki özellik sayısını döndürür. |
| [clear()](#clear--) | Tüm özellikleri kaldırır. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki özellik sayısını döndürür. Salt-okunur int.

**Döndürür:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Koleksiyona bir özellik ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Özelliğin adı. |
| value | java.lang.String | Özelliğin değeri. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Belirtilen ada sahip bir özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak özelliğin adı. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Özelliği döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Özelliğin adı. |

**Döndürür:**
java.lang.String - Özellik.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Özelliği döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Özelliğin adı. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Koleksiyondaki özellik sayısını döndürür. Salt-okunur [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Döndürür:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Tüm özellikleri kaldırır.