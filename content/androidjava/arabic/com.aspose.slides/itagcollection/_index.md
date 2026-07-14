---
title: ITagCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة الوسوم التي هي أزواج من السلاسل المعرفة من قبل المستخدم
type: docs
url: /ar/com.aspose.slides/itagcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

يمثل مجموعة الوسوم (أزواج من السلاسل المعرفة من قبل المستخدم)
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | يضيف وسماً جديداً إلى المجموعة. |
| [remove(String name)](#remove-java.lang.String-) | يزيل الوسم ذو الاسم المحدد من المجموعة. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | يعيد الفهرس القائم على الصفر للمفتاح المحدد في المجموعة. |
| [contains(String name)](#contains-java.lang.String-) | يحدد ما إذا كانت المجموعة تحتوي على اسم محدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل الوسم في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع الوسوم من المجموعة. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | يعيد قيمة وسم في الفهرس المحدد. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | يعيد مفتاح وسم في الفهرس المحدد. |
| [getNamesOfTags()](#getNamesOfTags--) | يعيد أسماء الوسوم. |
| [get_Item(String name)](#get-Item-java.lang.String-) | يعيد أو يضبط زوج المفتاح والقيمة لوسم. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | يعيد أو يضبط زوج المفتاح والقيمة لوسم. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

يضيف وسماً جديداً إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الوسم. |
| value | java.lang.String | قيمة الوسم. |

**القيمة المرجعة:**
int - الفهرس للوسم المضاف.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

يزيل الوسم ذو الاسم المحدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الوسم الذي سيُزال. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

يعيد الفهرس القائم على الصفر للمفتاح المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | الاسم للبحث عنه في المجموعة. |

**القيمة المرجعة:**
int - الفهرس القائم على الصفر للمفتاح، إذا وجد المفتاح في المجموعة؛ وإلا، -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

يحدد ما إذا كانت المجموعة تحتوي على اسم محدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | المفتاح للبحث عنه. |

**القيمة المرجعة:**
boolean - صحيح إذا كانت المجموعة تحتوي على وسم بالمفتاح المحدد؛ وإلا، خطأ.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل الوسم في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للوسم الذي سيُزال. |
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع الوسوم من المجموعة.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

يعيد قيمة وسم في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الوسم للارجاع. |

**القيمة المرجعة:**
java.lang.String - قيمة الوسم.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

يعيد مفتاح وسم في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الوسم للارجاع. |

**القيمة المرجعة:**
java.lang.String - مفتاح الوسم.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

يعيد أسماء الوسوم.

**القيمة المرجعة:**
java.lang.String[] - أسماء الوسوم.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

يعيد أو يضبط زوج المفتاح والقيمة لوسم.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | مفتاح الوسم. |

**القيمة المرجعة:**
java.lang.String - قيمة الوسم.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

يعيد أو يضبط زوج المفتاح والقيمة لوسم.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | مفتاح الوسم. |
| value | java.lang.String |  |