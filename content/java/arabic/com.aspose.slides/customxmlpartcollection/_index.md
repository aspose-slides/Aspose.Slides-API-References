---
title: CustomXmlPartCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من أجزاء XML المخصصة.
type: docs
url: /ar/com.aspose.slides/customxmlpartcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

يمثل مجموعة من أجزاء XML المخصصة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد العنصر في الفهرس المحدد. |
| [size()](#size--) | يعيد عدد أجزاء XML المخصصة في المجموعة. |
| [add(String xmlString)](#add-java.lang.String-) | يضيف جزء XML مخصص جديد. |
| [add(byte[] xmlData)](#add-byte---) | يضيف جزء XML مخصص جديد. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | يضيف جزء XML مخصص جديد. |
| [removeAt(int index)](#removeAt-int-) | يزيل جزء XML مخصص في الفهرس المحدد. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | يزيل أول ظهور لكائن معين من المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تُظهر ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر التزامن. |
| [iterator()](#iterator--) | يعيد عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر java للمجموعة بأكملها. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

يعيد العنصر في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس مبني على الصفر للعنصر المراد الحصول عليه. |

**الإرجاع:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - العنصر في الفهرس المحدد.

### size() {#size--}
```
public final int size()
```

يعيد عدد أجزاء XML المخصصة في المجموعة. int للقراءة فقط.

**الإرجاع:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlString | java.lang.String | سلسلة XML للجزء الجديد المراد إضافته. |

**الإرجاع:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlData | byte[] | بيانات XML للجزء الجديد المراد إضافته. |

**الإرجاع:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | java.io.InputStream | دفق الإدخال الذي يحتوي على بيانات XML للجزء الجديد المراد إضافته. |

**الإرجاع:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل جزء XML مخصص في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس مبني على الصفر للعنصر المراد إزالته. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

يزيل أول ظهور لكائن معين من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | جزء XML المخصص المراد إزالته. |

**الإرجاع:**
boolean - true إذا تم إزالة العنصر بنجاح؛ وإلا false.

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة التي سيتم النسخ إليها. |
| index | int | الفهرس لبدء النسخ. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تُظهر ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). للقراءة فقط boolean.

**الإرجاع:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر التزامن. للقراءة فقط Object.

**الإرجاع:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

يعيد عدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

يعيد مكرّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - An java.util.Iterator for the entire collection.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject