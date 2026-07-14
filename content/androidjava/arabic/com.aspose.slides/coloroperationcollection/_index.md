---
title: ColorOperationCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
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
| [size()](#size--) | يرجع عدد العمليات في مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يرجع أو يعيّن العملية عند الفهرس المحدد. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | يرجع أو يعيّن العملية عند الفهرس المحدد. |
| [add(int operation, float parameter)](#add-int-float-) | يضيف عملية جديدة إلى نهاية المجموعة. |
| [add(int operation)](#add-int-) | يضيف عملية جديدة إلى نهاية المجموعة. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | يدرج العملية الجديدة في مجموعة. |
| [insert(int position, int operation)](#insert-int-int-) | يدرج العملية الجديدة في مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل عملية اللون من مجموعة. |
| [clear()](#clear--) | يزيل جميع عمليات اللون. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرّرًا (iterator) جافا للمجموعة كاملة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر التزامن. |
| [deepClone()](#deepClone--) | ينشئ نسخة من مجموعة ColorOperationCollection. |
| [cloneT()](#cloneT--) | ينسخ الكائن الحالي |
### size() {#size--}
```
public final int size()
```

يرجع عدد العمليات في مجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

يرجع أو يعيّن العملية عند الفهرس المحدد. قراءة/كتابة [ColorOperation](../../com.aspose.slides/coloroperation).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

يرجع أو يعيّن العملية عند الفهرس المحدد. قراءة/كتابة [ColorOperation](../../com.aspose.slides/coloroperation).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

يضيف عملية جديدة إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| operation | int | نوع العملية. |
| parameter | float | معلمة العملية. |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - العملية المضافة.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

يضيف عملية جديدة إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| operation | int | نوع العملية. |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - العملية المضافة.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

يدرج العملية الجديدة في مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| position | int | الفهرس الذي سيتم إدراج العملية عنده. |
| operation | int | نوع العملية. |
| parameter | float | معلمة العملية. |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - العملية المدخلة.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

يدرج العملية الجديدة في مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| position | int | الفهرس الذي سيتم إدراج العملية عنده. |
| operation | int | نوع العملية. |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - العملية المدخلة.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل عملية اللون من مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس عملية اللون التي سيتم إزالتها. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع عمليات اللون.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

يرجع مكرّرًا (iterator) جافا للمجموعة كاملة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - java.util.Iterator للمجموعة كاملة.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس البداية في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. للقراءة فقط Object.

**القيمة المرجعة:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

ينشئ نسخة من مجموعة ColorOperationCollection.

**القيمة المرجعة:**
java.lang.Object - مجموعة [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) جديدة.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

ينسخ الكائن الحالي

**القيمة المرجعة:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - النسخة المستنسخة