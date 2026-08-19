---
title: SmartArtNodeCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مجموعه‌ای از گره‌های SmartArt است.
type: docs
url: /fa/com.aspose.slides/smartartnodecollection/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

نمایانگر مجموعه‌ای از گره‌های SmartArt است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | گره را بر اساس اندیس برمی‌گرداند |
| [size()](#size--) | تعداد گره‌ها در مجموعه را برمی‌گرداند فقط‌خواندنی int فقط‌خواندنی int. |
| [addNode()](#addNode--) | گره جدید SmartArt یا زیر گره‌ای را اضافه می‌کند. |
| [removeNode(int index)](#removeNode-int-) | گره یا زیر گره را بر اساس اندیس حذف می‌کند. |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | گره یا زیر گره را حذف می‌کند. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | گره جدیدی را در موقعیت انتخاب‌شدهٔ مجموعه گره‌ها اضافه می‌کند. |
| [iterator()](#iterator--) | یک شمارنده برمی‌گرداند که از میان مجموعه عبور می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | همهٔ عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

گره را بر اساس اندیس برمی‌گرداند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایهٔ عنصر |

**بازگرداندن:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - گرهٔ SmartArt
### size() {#size--}
```
public final int size()
```

تعداد گره‌ها در مجموعه را برمی‌گرداند فقط‌خواندنی int فقط‌خواندنی int.

**بازگرداندن:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

گره جدید SmartArt یا زیر گره‌ای را اضافه می‌کند.

**بازگرداندن:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - گره اضافه‌شده
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

گره یا زیر گره را بر اساس اندیس حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایهٔ گره |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

گره یا زیر گره را حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | گره برای حذف |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

گره جدیدی را در موقعیت انتخاب‌شدهٔ مجموعه گره‌ها اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | int | موقعیت صفر-پایهٔ گره |
**بازگرداندن:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - گره اضافه‌شده
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

یک شمارنده برمی‌گرداند که از میان مجموعه عبور می‌کند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - یک IGenericEnumerator که می‌تواند برای عبور از مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

همهٔ عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | اندیس شروع در آرایهٔ هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (thread-safe). فقط‌خواندنی boolean.

**بازگرداندن:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را برمی‌گرداند. فقط‌خواندنی Object.

**بازگرداندن:**
java.lang.Object