---
title: DrawingGuidesCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الأدلة القابلة للتعديل في الرسم.
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

يمثل مجموعة من الأدلة القابلة للتعديل في الرسم.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد دليل الرسم وفق الفهرس. |
| [add(byte orientation, float position)](#add-byte-float-) | يضيف دليل الرسم في نهاية المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل دليل الرسم في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [iterator()](#iterator--) | يعيد عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مُكرِّر java للمجموعة بأكملها. |
| [getCount()](#getCount--) | يعيد عدد العناصر في المجموعة. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |

### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

يعيد دليل الرسم وفق الفهرس. للقراءة فقط [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيم المرتجعة:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

يضيف دليل الرسم في نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| orientation | byte | اتجاه دليل الرسم. |
| position | float | موقع دليل الرسم بالنقاط. |

**القيم المرتجعة:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل دليل الرسم في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
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

يعيد عدادًا يتنقل عبر المجموعة.

**القيم المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

يعيد مُكرِّر java للمجموعة بأكملها.

**القيم المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - An java.util.Iterator for the entire collection.

### getCount() {#getCount--}
```
public final int getCount()
```

يعيد عدد العناصر في المجموعة. للقراءة فقط int.

**القيم المرتجعة:**
int

### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | المصفوفة المستهدفة. |
| index | int | الفهرس الابتدائي في المصفوفة المستهدفة. |