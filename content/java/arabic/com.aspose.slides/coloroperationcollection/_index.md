---
title: ColorOperationCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من عمليات تحويل اللون.
type: docs
url: /ar/com.aspose.slides/coloroperationcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

يمثل مجموعة من عمليات تحويل اللون.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | تعيد عدد العمليات في مجموعة. |
| [get_Item(int index)](#get-Item-int-) | تُعيد أو تُعيّن العملية في الفهرس المحدد. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | تُعيد أو تُعيّن العملية في الفهرس المحدد. |
| [add(int operation, float parameter)](#add-int-float-) | تضيف عملية جديدة إلى نهاية المجموعة. |
| [add(int operation)](#add-int-) | تضيف عملية جديدة إلى نهاية المجموعة. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | تُدرج العملية الجديدة في مجموعة. |
| [insert(int position, int operation)](#insert-int-int-) | تُدرج العملية الجديدة في مجموعة. |
| [removeAt(int index)](#removeAt-int-) | تزيل عملية اللون من مجموعة. |
| [clear()](#clear--) | تزيل جميع عمليات اللون. |
| [iterator()](#iterator--) | تعيد مُعدِّدًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | تعيد مكرِّر جافا للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تنسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | تعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا عبر الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | تعيد جذر المزامنة. |
| [deepClone()](#deepClone--) | تنشئ نسخة من مجموعة ColorOperationCollection. |
| [cloneT()](#cloneT--) | ينسخ الكائن الحالي |

### size() {#size--}
```
public final int size()
```

تعيد عدد العمليات في مجموعة. قراءة فقط int.

**الإرجاع:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

تُعيد أو تُعيّن العملية في الفهرس المحدد. قراءة/كتابة [ColorOperation](../../com.aspose.slides/coloroperation).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

تُعيد أو تُعيّن العملية في الفهرس المحدد. قراءة/كتابة [ColorOperation](../../com.aspose.slides/coloroperation).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

تضيف عملية جديدة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operation | int | نوع العملية. |
| parameter | float | معامل العملية. |

**الإرجاع:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملية مضافة.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

تضيف عملية جديدة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operation | int | نوع العملية. |

**الإرجاع:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملية مضافة.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

تُدرج العملية الجديدة في مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | int | الفهرس الذي ستُدرج فيه العملية. |
| operation | int | نوع العملية. |
| parameter | float | معامل العملية. |

**الإرجاع:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملية مُدرجة.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

تُدرج العملية الجديدة في مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | int | الفهرس الذي ستُدرج فيه العملية. |
| operation | int | نوع العملية. |

**الإرجاع:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملية مُدرجة.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

تزيل عملية اللون من مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس عملية اللون التي ستُزال. |

### clear() {#clear--}
```
public final void clear()
```

تزيل جميع عمليات اللون.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

تعيد مُعدِّدًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - يمكن استخدام IGenericEnumerator للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

تعيد مكرِّر جافا للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - java.util.Iterator للمجموعة بأكملها.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تنقل جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | الفهرس الأولي في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

تعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا عبر الخيوط). قراءة فقط boolean.

**الإرجاع:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

تعيد جذر المزامنة. قراءة فقط Object.

**الإرجاع:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

تنشئ نسخة من مجموعة ColorOperationCollection.

**الإرجاع:**
java.lang.Object - كائن java.lang.Object - مجموعة [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) جديدة.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

ينسخ الكائن الحالي

**الإرجاع:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - نسخة