---
title: IDrawingGuidesCollection
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل مجموعة من أدلة الرسم القابلة للتعديل.
type: docs
url: /ar/com.aspose.slides/idrawingguidescollection/
---
**جميع الواجهات المنفذة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

يمثل مجموعة من أدلة الرسم القابلة للتعديل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع دليل الرسم حسب الفهرس. |
| [add(byte orientation, float position)](#add-byte-float-) | يضيف دليل الرسم في نهاية المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل دليل الرسم عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد جميع العناصر في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

يرجع دليل الرسم حسب الفهرس. للقراءة فقط [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

يضيف دليل الرسم في نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| orientation | byte | اتجاه دليل الرسم. |
| position | float | موضع دليل الرسم بالنقاط. |

**القيمة المرجعة:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل دليل الرسم عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس دليل الرسم الذي يجب حذفه. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.

### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد جميع العناصر في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int