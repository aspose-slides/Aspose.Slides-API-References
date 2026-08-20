---
title: VbaModuleCollection
second_title: مرجع API الخاص بـ Aspose.Slides للغة جافا
description: يمثل مجموعة من وحدات مشروع VBA.
type: docs
url: /ar/com.aspose.slides/vbamodulecollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

يمثل مجموعة من وحدات مشروع VBA.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | يزيل أول حدوث لكائن محدد من المجموعة. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | يضيف وحدة فارغة جديدة إلى مشروع VBA. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [iterator()](#iterator--) | يرجع مُعدِّدًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مُكرِّر java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر التزامن. |
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط int.

**الإرجاع:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

يزيل أول حدوث لكائن محدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | الوحدة التي يجب إزالتها من المجموعة. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

يضيف وحدة فارغة جديدة إلى مشروع VBA.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الوحدة |

**الإرجاع:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - الوحدة التي تم إضافتها.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

يرجع مُعدِّدًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

يرجع مُكرِّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | الفهرس البداية في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). قراءة فقط boolean.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. قراءة فقط Object.

**الإرجاع:**
java.lang.Object