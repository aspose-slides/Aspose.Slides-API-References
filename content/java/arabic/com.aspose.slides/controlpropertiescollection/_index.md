---
title: ControlPropertiesCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: مجموعة من خصائص AcitveX.
type: docs
url: /ar/com.aspose.slides/controlpropertiescollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

مجموعة من خصائص AcitveX.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | يضيف خاصية إلى المجموعة. |
| [remove(String name)](#remove-java.lang.String-) | يزيل خاصية بالاسم المحدد. |
| [get_Item(String name)](#get-Item-java.lang.String-) | إرجاع أو تعيين الخاصية. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | إرجاع أو تعيين الخاصية. |
| [getNamesOfProperties()](#getNamesOfProperties--) | إرجاع مجموعة أسماء الخصائص. |
| [clear()](#clear--) | يزيل جميع الخصائص. |
| [getCount()](#getCount--) | إرجاع عدد الخصائص في المجموعة. |
| [iterator()](#iterator--) | إرجاع عدّاد يمر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرّر جافا للمجموعة الكاملة. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

يضيف خاصية إلى المجموعة.

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |
| value | java.lang.String | قيمة الخاصية. |
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

يزيل خاصية بالاسم المحدد.

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية التي تُزيل. |
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

إرجاع أو تعيين الخاصية.

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |

**الإرجاع:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

إرجاع أو تعيين الخاصية.

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |
| value | java.lang.String |  |
### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

إرجاع مجموعة أسماء الخصائص. للقراءة فقط [IGenericCollection](../../com.aspose.slides/igenericcollection).

**الإرجاع:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع الخصائص.
### getCount() {#getCount--}
```
public final int getCount()
```

إرجاع عدد الخصائص في المجموعة. int للقراءة فقط.

**الإرجاع:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

إرجاع عدّاد يمر عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

إرجاع مكرّر جافا للمجموعة الكاملة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.