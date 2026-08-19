---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایش‌دهنده مجموعه‌ای از اشیاء Summary Zoom Section.
type: docs
url: /fa/com.aspose.slides/summaryzoomsectioncollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)  
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

نمایش‌دهنده یک مجموعه از اشیاء Summary Zoom Section.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در شاخص مشخص شده قرار دارد، دریافت می‌کند. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | یک شیء جدید Summary Zoom Section ایجاد کرده و به مجموعه اضافه می‌کند |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند، دریافت می‌کند. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | شاخص شیء SummaryZoomSection مشخص‌شده را برمی‌گرداند. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | شیء Summary Zoom Section را از مجموعه حذف می‌کند. |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | عنصر Summary Zoom Section را برای بخش داده‌شده برمی‌گرداند. |
| [clear()](#clear--) | تمام اشیاء SummaryZoomSection را از مجموعه حذف می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را در آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همزمان (thread-safe) است یا خیر. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همزمانی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator برمی‌گرداند که در مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

عنصری را که در شاخص مشخص شده قرار دارد، دریافت می‌کند. فقط-خواندنی [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

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

**بازگشت:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)

### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

یک شیء جدید Summary Zoom Section ایجاد کرده و به مجموعه اضافه می‌کند

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
| section | [ISection](../../com.aspose.slides/isection) | Section برای عنصر جدید Summary Zoom Section [ISection](../../com.aspose.slides/isection)

اگر برای این بخش در مجموعه قبلاً عنصری وجود داشته باشد، عنصر موجود برگردانده می‌شود. |

**بازگشت:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - عنصر [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) اضافه‌شده

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند، دریافت می‌کند. فقط-خواندنی int.

**بازگشت:**
int

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

شاخص شیء SummaryZoomSection مشخص‌شده را برمی‌گرداند.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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

**بازگشت:**
int - شاخص شیء SummaryZoomSection یا -1 اگر شیء SummaryZoomSection از این مجموعه نباشد.

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

شیء Summary Zoom Section را از مجموعه حذف می‌کند.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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
| section | [ISection](../../com.aspose.slides/isection) | Section که عنصر Summary Zoom Section آن باید حذف شود [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

عنصر Summary Zoom Section را برای بخش داده‌شده برمی‌گرداند.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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
| section | [ISection](../../com.aspose.slides/isection) | Section برای یافتن [ISection](../../com.aspose.slides/isection) |

**بازگشت:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) یا null اگر مجموعه عنصری برای این بخش نداشته باشد.

### clear() {#clear--}
```
public final void clear()
```

تمام اشیاء SummaryZoomSection را از مجموعه حذف می‌کند.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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

کل مجموعه را در آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف |
| index | int | شاخص در آرایهٔ هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همزمان (thread-safe) است یا خیر. فقط-خواندنی boolean.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همزمانی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

یک enumerator برمی‌گرداند که در مجموعه پیمایش می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - یک java.util.Iterator برای کل مجموعه.