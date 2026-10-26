---
title: ISummaryZoomFrame
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر یک فریم Summary Zoom در یک اسلاید است.
type: docs
url: /fa/com.aspose.slides/isummaryzoomframe/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

نماینده یک فریم Summary Zoom در یک اسلاید است.
## متدها

| متد | توضیح |
| --- | --- |
| [getLayout()](#getLayout--) | دریافت نمای‌بندی بخش‌های Summary Zoom در فریم. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | دریافت [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) برای شیء Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

دریافت نمای‌بندی بخش‌های Summary Zoom در فریم. مقدار پیش‌فرض GridLayout است.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**  
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

دریافت [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) برای شیء Summary Zoom Frame.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**  
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)