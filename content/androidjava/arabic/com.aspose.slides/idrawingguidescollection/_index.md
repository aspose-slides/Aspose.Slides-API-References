---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Android عبر مرجع API جافا
description: يمثل مجموعة من الأدلة القابلة للتعديل للرسم.
type: docs
url: /ar/com.aspose.slides/idrawingguidescollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

يمثل مجموعة من الأدلة القابلة للتعديل للرسم.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the drawing guide by index. |
| [add(byte orientation, float position)](#add-byte-float-) | Adds the drawing guide at the end of the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the drawing guide at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Gets the number of all elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Returns the drawing guide by index. للقراءة فقط [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة الراجعة:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Adds the drawing guide at the end of the collection.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| orientation | byte | Orientation of the drawing guide. |
| position | float | Position of the the drawing guide in points. |

**القيمة الراجعة:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the drawing guide at the specified index.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | Index of the drawing guide that should be deleted. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of all elements in the collection. للقراءة فقط int.

**القيمة الراجعة:**
int