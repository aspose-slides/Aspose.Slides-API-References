---
title: CustomXmlPartCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من أجزاء XML المخصصة.
type: docs
url: /ar/com.aspose.slides/customxmlpartcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُطبقة:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

يمثل مجموعة من أجزاء XML المخصصة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع العنصر في الفهرس المحدد. |
| [size()](#size--) | يرجع عدد أجزاء XML المخصصة في المجموعة. |
| [add(String xmlString)](#add-java.lang.String-) | يضيف جزء XML مخصص جديد. |
| [add(byte[] xmlData)](#add-byte---) | يضيف جزء XML مخصص جديد. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | يضيف جزء XML مخصَّص جديد. |
| [removeAt(int index)](#removeAt-int-) | يزيل جزء XML مخصص في الفهرس المحدد. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | يزيل أول حدوث لكائن محدد من المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ إلى مصفوفة محددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامناً (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر التزامن. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مُكرر Java للمجموعة بأكملها. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

يرجع العنصر في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد الحصول عليه. |

**العائد:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - العنصر في الفهرس المحدد.

### size() {#size--}
```
public final int size()
```

يرجع عدد أجزاء XML المخصصة في المجموعة. int للقراءة فقط.

**العائد:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlString | java.lang.String | سلسلة XML للجزء الجديد الذي سيُضاف. |

**العائد:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlData | byte[] | بيانات XML للجزء الجديد الذي سيُضاف. |

**العائد:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | java.io.InputStream | دفق الإدخال الذي يحتوي على بيانات XML للجزء الجديد الذي سيُضاف. |

**العائد:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل جزء XML مخصص في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

يزيل أول حدوث لكائن محدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | جزء XML المخصص الذي سيُزال. |

**العائد:**
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

نسخ إلى مصفوفة محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة التي سيُنسخ إليها. |
| index | int | الفهرس لبدء النسخ. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامناً (thread-safe). boolean للقراءة فقط.

**العائد:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. Object للقراءة فقط.

**العائد:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**العائد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - يمكن استخدام IGenericEnumerator للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

يرجع مُكرر Java للمجموعة بأكملها.

**العائد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - java.util.Iterator للمجموعة بأكملها.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**العائد:**
com.aspose.slides.IDOMObject