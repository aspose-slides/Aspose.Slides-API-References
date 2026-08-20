---
title: ITagCollection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل مجموعة العلامات (أزواج السلاسل المعرفة من قبل المستخدم)
type: docs
url: /ar/com.aspose.slides/itagcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

يمثل مجموعة العلامات (أزواج السلاسل المعرفة من قبل المستخدم)
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | يضيف علامة جديدة إلى المجموعة. |
| [remove(String name)](#remove-java.lang.String-) | يزيل العلامة ذات الاسم المحدد من المجموعة. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | يعيد الفهرس الصفري للمفتاح المحدد في المجموعة. |
| [contains(String name)](#contains-java.lang.String-) | يحدد ما إذا كانت المجموعة تحتوي على اسم معين. |
| [removeAt(int index)](#removeAt-int-) | يزيل العلامة في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العلامات من المجموعة. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | يعيد قيمة العلامة في الفهرس المحدد. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | يعيد مفتاح العلامة في الفهرس المحدد. |
| [getNamesOfTags()](#getNamesOfTags--) | يعيد أسماء العلامات. |
| [get_Item(String name)](#get-Item-java.lang.String-) | يعيد أو يضبط زوج المفتاح والقيمة لعلامة. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | يعيد أو يضبط زوج المفتاح والقيمة لعلامة. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

يضيف علامة جديدة إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم العلامة. |
| value | java.lang.String | قيمة العلامة. |

**القيمة المرجعة:**
int - فهرس العلامة المضافة.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

يزيل العلامة ذات الاسم المحدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم العلامة التي سيتم إزالتها. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

يعيد الفهرس الصفري للمفتاح المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | الاسم للعثور عليه في المجموعة. |

**القيمة المرجعة:**
int - الفهرس الصفري للمفتاح إذا تم العثور على المفتاح في المجموعة؛ وإلا -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

يحدد ما إذا كانت المجموعة تحتوي على اسم معين.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | المفتاح للعثور عليه. |

**القيمة المرجعة:**
boolean - true إذا كانت المجموعة تحتوي على علامة بالمفتاح المحدد؛ وإلا false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العلامة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعلامة التي سيتم إزالتها. |
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العلامات من المجموعة.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

يعيد قيمة العلامة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العلامة لإرجاعها. |

**القيمة المرجعة:**
java.lang.String - قيمة العلامة.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

يعيد مفتاح العلامة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العلامة لإرجاعها. |

**القيمة المرجعة:**
java.lang.String - مفتاح العلامة.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

يعيد أسماء العلامات.

**القيمة المرجعة:**
java.lang.String[] - أسماء العلامات.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

يعيد أو يضبط زوج المفتاح والقيمة لعلامة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | مفتاح العلامة. |

**القيمة المرجعة:**
java.lang.String - قيمة العلامة.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

يعيد أو يضبط زوج المفتاح والقيمة لعلامة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | مفتاح العلامة. |
| value | java.lang.String |  |