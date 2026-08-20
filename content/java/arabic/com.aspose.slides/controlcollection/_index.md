---
title: ControlCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
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
| [size()](#size--) | إرجاع عدد من الكائنات في المجموعة. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | إنشاء وإضافة عنصر تحكم جديد إلى المجموعة. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | إزالة عنصر تحكم ActiveX من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة عنصر تحكم ActiveX المخزن في الموضع المحدد من المجموعة. |
| [clear()](#clear--) | إزالة جميع عناصر التحكم من المجموعة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع عنصر تحكم في الموضع المحدد. |
| [iterator()](#iterator--) | إرجاع عدّاد يمرّ عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرّر java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ المجموعة بأكملها إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن عبر الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر التزامن. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

إرجاع عدد من الكائنات في المجموعة. قراءة فقط int.

**الإرجاع:**  
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

إنشاء وإضافة عنصر تحكم جديد إلى المجموعة.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| controlType | int | نوع عنصر التحكم للإضافة. |
| x | float | إحداثي X للجانب الأيسر لإطار الشكل. |
| y | float | إحداثي Y للجانب العلوي لإطار الشكل. |
| width | float | عرض إطار الشكل. |
| height | float | ارتفاع إطار الشكل. |

**الإرجاع:**  
[IControl](../../com.aspose.slides/icontrol) - عنصر التحكم المُنشأ.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

إزالة عنصر تحكم ActiveX من المجموعة.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | عنصر تحكم للإزالة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

إزالة عنصر تحكم ActiveX المخزن في الموضع المحدد من المجموعة.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس عنصر التحكم للإزالة. |

### clear() {#clear--}
```
public final void clear()
```

إزالة جميع عناصر التحكم من المجموعة.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

إرجاع عنصر تحكم في الموضع المحدد.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس عنصر التحكم. |

**الإرجاع:**  
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

إرجاع عدّاد يمرّ عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - مُعدد IGenericEnumerator يمكن استخدامه لتكرار عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

إرجاع مكرّر java للمجموعة بأكملها.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - java.util.Iterator للمجموعة بأكملها.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ المجموعة بأكملها إلى المصفوفة المحددة.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف |
| index | int | فهرس في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن عبر الخيوط). قراءة فقط boolean.

**الإرجاع:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر التزامن. قراءة فقط Object.

**الإرجاع:**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject