---
title: ExtraColorSchemeCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من مخططات الألوان الإضافية.
type: docs
url: /ar/com.aspose.slides/extracolorschemecollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject  
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

يمثل مجموعة من مخططات الألوان الإضافية.

## الطرق

| الدالة | الوصف |
| --- | --- |
| [size()](#size--) | يعيد عدد العناصر في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد مخطط لون حسب الفهرس. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | يعيد مُعدِّدًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرِّر جافا للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع عناصر المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى ArrayList متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد كائنًا يمكن استخدامه لمزامنة الوصول إلى المجموعة. |

### size() {#size--}
```
public final int size()
```

يعيد عدد العناصر في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

يعيد مخطط لون حسب الفهرس. للقراءة فقط [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**  
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent\_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**  
com.aspose.slides.IDOMObject

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

يعيد مُعدِّدًا يتنقل عبر المجموعة.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

يعيد مكرِّر جافا للمجموعة بأكملها.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع عناصر المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى ArrayList متزامنًا (آمن للخيوط). للقراءة فقط boolean.

**القيمة المرجعة:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد كائنًا يمكن استخدامه لمزامنة الوصول إلى المجموعة. للقراءة فقط Object.

يعيد جذر المزامنة. للقراءة فقط Object.

**القيمة المرجعة:**  
java.lang.Object