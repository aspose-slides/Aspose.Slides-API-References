---
title: IControlPropertiesCollection
second_title: مرجع Aspose.Slides لـ Java API
description: مجموعة من عناصر التحكم ActiveX.
type: docs
url: /ar/com.aspose.slides/icontrolpropertiescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

مجموعة من عناصر التحكم ActiveX.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يرجع عددًا من الخصائص في المجموعة. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | يضيف خاصية إلى المجموعة. |
| [remove(String name)](#remove-java.lang.String-) | يزيل خاصية بالاسم المحدد. |
| [get_Item(String name)](#get-Item-java.lang.String-) | يرجع أو يعيّن الخاصية. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | يرجع أو يعيّن الخاصية. |
| [getNamesOfProperties()](#getNamesOfProperties--) | يرجع عددًا من الخصائص في المجموعة. |
| [clear()](#clear--) | يزيل جميع الخصائص. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


يرجع عددًا من الخصائص في المجموعة. int للقراءة فقط.

**الإرجاع:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


يضيف خاصية إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |
| value | java.lang.String | قيمة الخاصية. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


يزيل خاصية بالاسم المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية لإزالتها. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


يرجع أو يعيّن الخاصية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |

**الإرجاع:**
java.lang.String - خاصية.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


يرجع أو يعيّن الخاصية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


يرجع عددًا من الخصائص في المجموعة. [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط.

**الإرجاع:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


يزيل جميع الخصائص.