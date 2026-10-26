---
title: ControlCollection
second_title: Aspose.Slides لأندرويد عبر واجهة برمجة تطبيقات جافا
description: مجموعة من عناصر التحكم ActiveX.
type: docs
url: /ar/com.aspose.slides/controlcollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject  
```
public class ControlCollection implements IControlCollection, IDOMObject
```

مجموعة من عناصر التحكم ActiveX.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يعيد عدد العناصر في المجموعة. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | ينشئ عنصر تحكم جديد ويضيفه إلى المجموعة. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | يزيل عنصر تحكم ActiveX من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل عنصر تحكم ActiveX المخزن في الموضع المحدد من المجموعة. |
| [clear()](#clear--) | يزيل جميع عناصر التحكم من المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد عنصر تحكم في الموضع المحدد. |
| [iterator()](#iterator--) | يعيد عدادًا (enumerator) يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرر Java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ المجموعة بأكملها إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخطوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر التزامن. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

يعيد عدد العناصر في المجموعة. قراءة فقط int.

**الإرجاع:**  
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

ينشئ عنصر تحكم جديد ويضيفه إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| controlType | int | نوع عنصر التحكم لإضافته. |
| x | float | الإحداثي X للجانب الأيسر لإطار الشكل. |
| y | float | الإحداثي Y للجانب العلوي لإطار الشكل. |
| width | float | عرض إطار الشكل. |
| height | float | ارتفاع إطار الشكل. |

**الإرجاع:**  
[IControl](../../com.aspose.slides/icontrol) - عنصر التحكم الذي تم إنشاؤه.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

يزيل عنصر تحكم ActiveX من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | عنصر تحكم للإزالة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل عنصر تحكم ActiveX المخزن في الموضع المحدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس عنصر التحكم للإزالة. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع عناصر التحكم من المجموعة.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

يعيد عنصر تحكم في الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس عنصر التحكم. |

**الإرجاع:**  
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

يعيد عدادًا (enumerator) يتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

يعيد مكرر Java للمجموعة بأكملها.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ المجموعة بأكملها إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف |
| index | int | فهرس في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخطوط). قراءة فقط boolean.

**الإرجاع:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر التزامن. قراءة فقط Object.

**الإرجاع:**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject