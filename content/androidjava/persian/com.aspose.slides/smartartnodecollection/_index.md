---
title: SmartArtNodeCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مجموعه‌ای از گره‌های SmartArt را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/smartartnodecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

نمایش یک مجموعه از گره‌های SmartArt.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns node by index |
| [size()](#size--) | Returns count of nodes in collection Read-only  int  Read-only  int . |
| [addNode()](#addNode--) | Add new smart art node or sub node. |
| [removeNode(int index)](#removeNode-int-) | Remove node or sub node by index |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Remove node or sub node |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Add new node in the selected position of nodes collection |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

گره را بر حسب اندیس بر می‌گرداند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | The zero-based index of the element |

**مقدار بازگشتی:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - گره SmartArt
### size() {#size--}
```
public final int size()
```

تعداد گره‌ها را در مجموعه بر می‌گرداند فقط-خواندنی int فقط-خواندنی int .

**مقدار بازگشتی:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

یک گره جدید smart art یا گره فرعی اضافه می‌کند.

**مقدار بازگشتی:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - گره اضافه‌شده
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

گره یا گره فرعی را بر حسب اندیس حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | Zero-based index of node |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

گره یا گره فرعی را حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | گره برای حذف |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

یک گره جدید را در موقعیت انتخاب‌شدهٔ مجموعه گره‌ها اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | int | موقعیت گره بر پایه صفر |

**مقدار بازگشتی:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - گره اضافه‌شده
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

یک شمارشگر را بر می‌گرداند که از میان مجموعه پیمایش می‌کند.

**مقدار بازگشتی:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - یک IGenericEnumerator که می‌توان برای پیمایش مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

یک java iterator برای کل مجموعه بر می‌گرداند.

**مقدار بازگشتی:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را بر می‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (thread-safe). فقط-خواندنی boolean .

**مقدار بازگشتی:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را بر می‌گرداند فقط-خواندنی Object.

**مقدار بازگشتی:**
java.lang.Object