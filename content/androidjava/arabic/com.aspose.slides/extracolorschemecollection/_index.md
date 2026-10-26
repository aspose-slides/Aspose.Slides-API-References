---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides لـ Android عبر مرجع API للجافا
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

يمثّل مجموعة من مخططات الألوان الإضافية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يعيد عددًا من العناصر int في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد مخطط لون حسب الفهرس. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | يعيد كائن تعداد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر جافا للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع عناصر المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى ArrayList متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد كائنًا يمكن استخدامه لمزامنة الوصول إلى المجموعة. |
### size() {#size--}
```
public final int size()
```

يعيد عددًا من العناصر int في المجموعة. قراءة-فقط int.

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

يعيد مخطط لون حسب الفهرس. قراءة-فقط [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة-فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

يعيد كائن تعداد يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

يعيد مكرّر جافا للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع عناصر المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة المستهدفة. |
| index | int | الفهرس الابتدائي في المصفوفة. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى ArrayList متزامنًا (آمن للخيوط). قراءة-فقط boolean.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد كائنًا يمكن استخدامه لمزامنة الوصول إلى المجموعة. قراءة-فقط Object.

يعيد جذر المزامنة. قراءة-فقط Object.

**القيمة المرجعة:**
java.lang.Object