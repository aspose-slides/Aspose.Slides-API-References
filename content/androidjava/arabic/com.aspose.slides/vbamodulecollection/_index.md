---
title: VbaModuleCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
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
| [size()](#size--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | يزيل أول ظهور لكائن محدد من المجموعة. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | يضيف وحدة فارغة جديدة إلى مشروع VBA. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [iterator()](#iterator--) | يُرجع عدّادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يُرجع مُكرّر Java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يُرجع قيمة تدل على ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخطوط). |
| [getSyncRoot()](#getSyncRoot--) | يُرجع جذر التزامن. |

### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الفعلية الموجودة في المجموعة. int للقراءة فقط.

**الإرجاع:**  
int

### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

يزيل أول ظهور لكائن محدد من المجموعة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | الوحدة التي تُزال من المجموعة. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

يضيف وحدة فارغة جديدة إلى مشروع VBA.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الوحدة |

**الإرجاع:**  
[IVbaModule](../../com.aspose.slides/ivbamodule) - الوحدة المضافة.

### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[IVbaModule](../../com.aspose.slides/ivbamodule)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

يُرجع عدّادًا يتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

يُرجع مُكرّر Java للمجموعة بأكملها.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - java.util.Iterator للمجموعة بأكملها.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | الفهرس الابتدائي في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يُرجع قيمة تدل على ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخطوط). boolean للقراءة فقط.

**الإرجاع:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يُرجع جذر التزامن. Object للقراءة فقط.

**الإرجاع:**  
java.lang.Object