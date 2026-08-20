---
title: TagCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة العلامات (أزواج سلاسل معرفة من قبل المستخدم)
type: docs
url: /ar/com.aspose.slides/tagcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

يمثل مجموعة العلامات (أزواج سلاسل معرفة من قبل المستخدم)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | إرجاع عدد من العلامات في المجموعة. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | إضافة علامة جديدة إلى المجموعة. |
| [remove(String name)](#remove-java.lang.String-) | إزالة العلامة التي لها اسم محدد من المجموعة. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | إرجاع الفهرس الصفري للمفتاح المحدد في المجموعة. |
| [contains(String name)](#contains-java.lang.String-) | تحديد ما إذا كانت المجموعة تحتوي على اسم محدد. |
| [removeAt(int index)](#removeAt-int-) | إزالة العلامة في الفهرس المحدد. |
| [clear()](#clear--) | إزالة جميع العلامات من المجموعة. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | إرجاع قيمة علامة في الفهرس المحدد. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | إرجاع مفتاح علامة في الفهرس المحدد. |
| [getNamesOfTags()](#getNamesOfTags--) | إرجاع أسماء العلامات. |
| [get_Item(String name)](#get-Item-java.lang.String-) | إرجاع أو تعيين زوج المفتاح والقيمة لعلامة. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | إرجاع أو تعيين زوج المفتاح والقيمة لعلامة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامن (آمن للخطوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر المزامنة. |
| [iterator()](#iterator--) | إرجاع عدّاد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مؤشر Java للمجموعة بأكملها. |
### size() {#size--}
```
public final int size()
```

إرجاع عدد من العلامات في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

إضافة علامة جديدة إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم العلامة. |
| value | java.lang.String | قيمة العلامة. |

**القيمة المرجعة:**
int - فهرس العلامة المضافة.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

إزالة العلامة التي لها اسم محدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم العلامة المراد إزالتها. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

إرجاع الفهرس الصفري للمفتاح المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | الاسم للبحث في المجموعة. |

**القيمة المرجعة:**
int - الفهرس الصفري للمفتاح إذا تم العثور على المفتاح في المجموعة؛ غير ذلك، -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

تحديد ما إذا كانت المجموعة تحتوي على اسم محدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | المفتاح للبحث. |

**القيمة المرجعة:**
boolean - صحيح إذا كانت المجموعة تحتوي على علامة بالمفتاح المحدد؛ غير ذلك، خطأ.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

إزالة العلامة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعلامة المراد إزالتها. |
### clear() {#clear--}
```
public final void clear()
```

إزالة جميع العلامات من المجموعة.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

إرجاع قيمة علامة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العلامة للرجوع إليها. |

**القيمة المرجعة:**
java.lang.String - قيمة علامة.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

إرجاع مفتاح علامة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العلامة للرجوع إليها. |

**القيمة المرجعة:**
java.lang.String - مفتاح علامة.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

إرجاع أسماء العلامات.

**القيمة المرجعة:**
java.lang.String[] - أسماء العلامات.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

إرجاع أو تعيين زوج المفتاح والقيمة لعلامة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | مفتاح العلامة. |

**القيمة المرجعة:**
java.lang.String - قيمة علامة.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

إرجاع أو تعيين زوج المفتاح والقيمة لعلامة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | مفتاح العلامة. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة للملء. |
| index | int | الموضع الابتدائي في مصفوفة الهدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامن (آمن للخطوط). boolean للقراءة فقط.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر المزامنة. Object للقراءة فقط.

**القيمة المرجعة:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

إرجاع عدّاد يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator يمكن استخدامها للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

إرجاع مؤشر Java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator كامل للمجموعة.