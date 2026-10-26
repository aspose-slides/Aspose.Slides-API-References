---
title: IControlPropertiesCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: مجموعة من عناصر التحكم ActiveX.
type: docs
url: /ar/com.aspose.slides/icontrolpropertiescollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

مجموعة من عناصر التحكم ActiveX.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | إرجاع عدد من الخصائص في المجموعة. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | إضافة خاصية إلى المجموعة. |
| [remove(String name)](#remove-java.lang.String-) | إزالة خاصية بالاسم المحدد. |
| [get_Item(String name)](#get-Item-java.lang.String-) | إرجاع أو تعيين الخاصية. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | إرجاع أو تعيين الخاصية. |
| [getNamesOfProperties()](#getNamesOfProperties--) | إرجاع عدد من الخصائص في المجموعة. |
| [clear()](#clear--) | إزالة جميع الخصائص. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

يعيد عددًا من الخصائص في المجموعة. قراءة فقط int.

**القيم المرجعة:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

يضيف خاصية إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |
| value | java.lang.String | قيمة الخاصية. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

يزيل خاصية بالاسم المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية التي سيتم إزالتها. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

إرجاع أو تعيين الخاصية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |

**القيم المرجعة:**
java.lang.String - الخاصية.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

إرجاع أو تعيين الخاصية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الخاصية. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

إرجاع عدد من الخصائص في المجموعة. قراءة فقط [IGenericCollection](../../com.aspose.slides/igenericcollection).

**القيم المرجعة:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

إزالة جميع الخصائص.