---
title: ControlPropertiesCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
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
| [get_Item(String name)](#get-Item-java.lang.String-) | يرجع أو يضبط الخاصية. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | يرجع أو يضبط الخاصية. |
| [getNamesOfProperties()](#getNamesOfProperties--) | يرجع مجموعة أسماء الخصائص. |
| [clear()](#clear--) | يزيل جميع الخصائص. |
| [getCount()](#getCount--) | يرجع عدد الخصائص في المجموعة. |
| [iterator()](#iterator--) | يرجع عدّادًا يمر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرر java للمجموعة بأكملها. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

يضيف خاصية إلى المجموعة.

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |
| value | java.lang.String | قيمة الخاصية. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

يزيل خاصية بالاسم المحدد.

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية المراد إزالتها. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

يرجع أو يضبط الخاصية.

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |

**القيمة المرجعة:**
java.lang.String - خاصية.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

يرجع أو يضبط الخاصية.

**المعلمات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

يرجع مجموعة أسماء الخصائص. للقراءة فقط [IGenericCollection](../../com.aspose.slides/igenericcollection).

**القيمة المرجعة:**
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

يرجع عدد الخصائص في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

يرجع عدّادًا يمر عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator يمكن استخدامه للتجول عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

يرجع مكرر java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator للمجموعة بأكملها.