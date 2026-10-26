---
title: ISummaryZoomSectionCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش یک مجموعه از اشیاء Summary Zoom Section.
type: docs
url: /fa/com.aspose.slides/isummaryzoomsectioncollection/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

نمایش یک مجموعه از اشیاء Summary Zoom Section.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص دریافت می‌کند. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | یک شیء جدید Summary Zoom Section ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | عنصری از نوع Summary Zoom Section برای بخش داده شده برمی‌گرداند. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | شیء Summary Zoom Section را از مجموعه حذف می‌کند. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | ایندکس شیء SummaryZoomSection مشخص را برمی‌گرداند. |
| [clear()](#clear--) | تمام اشیای SummaryZoomSection را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

عنصر را در اندیس مشخص دریافت می‌کند. فقط‌خواندنی [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

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
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

یک شیء جدید Summary Zoom Section ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید

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
| section | [ISection](../../com.aspose.slides/isection) | بخش برای یک عنصر جدید Summary Zoom Section [ISection](../../com.aspose.slides/isection)

--------------------

اگر عنصری برای این بخش قبلاً در مجموعه وجود داشته باشد، عنصر موجود برگردانده می‌شود. |

**بازگشت:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - عنصر [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) اضافه‌شده
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

عنصری از نوع Summary Zoom Section برای بخش داده شده برمی‌گرداند.

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
| section | [ISection](../../com.aspose.slides/isection) | بخش برای جستجو [ISection](../../com.aspose.slides/isection) |

**بازگشت:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) یا null اگر مجموعه عنصری برای این بخش موجود نباشد.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
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
| section | [ISection](../../com.aspose.slides/isection) | بخشی که عنصر Summary Zoom Section آن باید حذف شود [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

ایندکس شیء SummaryZoomSection مشخص را برمی‌گرداند.

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
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | شیء SummaryZoomSection برای جستجو [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**بازگشت:**
int - ایندکس شیء SummaryZoomSection یا -1 اگر شیء SummaryZoomSection متعلق به این مجموعه نباشد.
### clear() {#clear--}
```
public abstract void clear()
```

تمام اشیای SummaryZoomSection را از مجموعه حذف می‌کند.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```
