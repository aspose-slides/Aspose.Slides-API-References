---
title: DrawingGuidesCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من الأدلة القابلة للتعديل للرسم.
type: docs
url: /ar/com.aspose.slides/drawingguidescollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)  
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

يمثل مجموعة من الأدلة القابلة للتعديل للرسم.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع دليل الرسم حسب الفهرس. |
| [add(byte orientation, float position)](#add-byte-float-) | يضيف دليل الرسم في نهاية المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل دليل الرسم في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [iterator()](#iterator--) | يرجع تعدادًا يتجول عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرِّر java للمجموعة بأكملها. |
| [getCount()](#getCount--) | يرجع عدد العناصر في المجموعة. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | يننسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |

### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

يرجع دليل الرسم حسب الفهرس. للقراءة فقط [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

يضيف دليل الرسم في نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| orientation | byte | اتجاه دليل الرسم. |
| position | float | موضع دليل الرسم بالنقاط. |

**القيمة المرجعة:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل دليل الرسم في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس دليل الرسم الذي يجب حذفه. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

يرجع تعدادًا يتجول عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - مُعدد IGenericEnumerator يمكن استخدامه للتجوال عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

يرجع مكرِّر java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - java.util.Iterator للمجموعة بأكملها.

### getCount() {#getCount--}
```
public final int getCount()
```

يرجع عدد العناصر في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int

### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | المصفوفة الهدف. |
| index | int | الفهرس البدئي في المصفوفة الهدف. |