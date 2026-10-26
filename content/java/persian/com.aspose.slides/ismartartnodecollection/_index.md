---
title: ISmartArtNodeCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک مجموعه از گره‌های SmartArt.
type: docs
url: /fa/com.aspose.slides/ismartartnodecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

نمایانگر یک مجموعه از گره‌های SmartArt است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | گره را بر اساس شاخص برمی‌گرداند. |
| [addNode()](#addNode--) | گره جدید یا زیرگره اضافه می‌کند. |
| [removeNode(int index)](#removeNode-int-) | گره یا زیرگره را بر اساس شاخص حذف می‌کند. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | گره یا زیرگره را حذف می‌کند. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | گره جدید را در موقعیت انتخاب‌شده از مجموعه گره‌ها اضافه می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

گره را بر اساس شاخص برمی‌گرداند. فقط‌خواندنی [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا برای عنصر. |

**بازگشت:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

گره جدید یا زیرگره‌ای اضافه می‌کند.

**بازگشت:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - گره اضافه‌شده
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

گره یا زیرگره را بر اساس شاخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا برای گره |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

گره یا زیرگره را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | گره برای حذف. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

گره جدید را در موقعیت انتخاب‌شده از مجموعه گره‌ها اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | int | موقعیت صفر پایه گره. |

**بازگشت:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - گره اضافه‌شده