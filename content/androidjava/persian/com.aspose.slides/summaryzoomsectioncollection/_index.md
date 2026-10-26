---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایندهٔ مجموعه‌ای از اشیاء Summary Zoom Section است.
type: docs
url: /fa/com.aspose.slides/summaryzoomsectioncollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

نمایندهٔ مجموعه‌ای از اشیاء Summary Zoom Section است.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در اندیس مشخص شده قرار دارد دریافت می‌کند. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | یک شیء جدید Summary Zoom Section ایجاد می‌کند و آن را به مجموعه اضافه می‌کند. |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | اندیس شیء SummaryZoomSection مشخص‌شده را باز می‌گرداند. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | شیء Summary Zoom Section را از مجموعه حذف می‌کند. |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | عنصر Summary Zoom Section مربوط به بخش داده‌شده را باز می‌گرداند. |
| [clear()](#clear--) | تمام اشیاء SummaryZoomSection را از مجموعه حذف می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را باز می‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همزمان (Thread-Safe) است یا خیر. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همزمانی را باز می‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه iterate می‌کند را باز می‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه باز می‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

عنصری را که در اندیس مشخص شده قرار دارد دریافت می‌کند. فقط-خواندنی [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گردد:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)

### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

یک شیء جدید Summary Zoom Section ایجاد می‌کند و آن را به مجموعه اضافه می‌کند.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخش برای عنصر جدید Summary Zoom Section [ISection](../../com.aspose.slides/isection)

--------------------
اگر عنصری برای این بخش از پیش در مجموعه وجود داشته باشد، عنصر موجود بازگردانده می‌شود. |

**باز می‌گردد:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Added [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) element

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. فقط-خواندنی int.

**باز می‌گردد:**
int

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

اندیس شیء SummaryZoomSection مشخص‌شده را باز می‌گرداند.

--------------------

> ```
> مثال نشان می‌دهد که چگونه عنصر Summary Zoom Section را بر اساس اندیس دریافت می‌کنیم:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | شیء SummaryZoomSection برای یافتن [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**باز می‌گردد:**
int - اندیس یک شیء SummaryZoomSection یا -1 اگر شیء SummaryZoomSection متعلق به این مجموعه نباشد.

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

شیء Summary Zoom Section را از مجموعه حذف می‌کند.

--------------------

> ```
> مثال نشان می‌دهد که چگونه عنصر Summary Zoom Section را بر اساس اندیس دریافت می‌کنیم:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که عنصر Summary Zoom Section آن باید حذف شود [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

عنصر Summary Zoom Section مربوط به بخش داده‌شده را باز می‌گرداند.

--------------------

> ```
> مثال نشان می‌دهد که چگونه عنصر Summary Zoom Section را بر اساس اندیس دریافت می‌کنیم:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخش برای یافتن [ISection](../../com.aspose.slides/isection) |

**باز می‌گردد:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) یا null اگر مجموعه عنصری برای این بخش نداشته باشد.

### clear() {#clear--}
```
public final void clear()
```

تمام اشیاء SummaryZoomSection را از مجموعه حذف می‌کند.

--------------------

> ```
> مثال نشان می‌دهد که چگونه عنصر Summary Zoom Section را بر اساس اندیس دریافت می‌کنیم:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

کل مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف |
| index | int | اندیس در آرایهٔ هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را باز می‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همزمان (Thread-Safe) است یا خیر. فقط-خواندنی boolean.

**باز می‌گردد:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همزمانی را باز می‌گرداند. فقط-خواندنی Object.

**باز می‌گردد:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

یک enumerator که از طریق مجموعه iterate می‌کند را باز می‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - یک IGenericEnumerator که می‌تواند برای iterating مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

یک java iterator برای کل مجموعه باز می‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - یک java.util.Iterator برای کل مجموعه.