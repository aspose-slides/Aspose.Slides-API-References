---
title: SmartArtShapeCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک مجموعه از اشکال SmartArt
type: docs
url: /fa/com.aspose.slides/smartartshapecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

یک مجموعه از اشکال SmartArt را نشان می‌دهد
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه وجود دارند را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص‌شده را برمی‌گرداند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [iterator()](#iterator--) | یک شمارنده را که از مجموعه عبور می‌کند، برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه وجود دارند را برمی‌گرداند. فقط-خواندنی int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

عنصر موجود در ایندکس مشخص‌شده را برمی‌گرداند. فقط-خواندنی [SmartArtShape](../../com.aspose.slides/smartartshape).

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس شکل |

**Returns:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - شکل SmartArt
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (thread-safe). فقط-خواندنی boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**Returns:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | ایندکس شروع در آرایهٔ هدف. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

یک شمارنده را که از مجموعه عبور می‌کند، برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - یک java.util.Iterator برای کل مجموعه.