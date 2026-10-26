---
title: ISummaryZoomFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک فریم Summary Zoom را در اسلاید نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/isummaryzoomframe/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

یک **Summary Zoom frame** را در اسلاید نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getLayout()](#getLayout--) | طرح‌بندی بخش‌های Summary Zoom را در فریم دریافت می‌کند. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) را برای شیء Summary Zoom Frame دریافت می‌کند. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


طرح‌بندی بخش‌های Summary Zoom را در فریم دریافت می‌کند. مقدار پیش‌فرض GridLayout است.

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


[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) را برای شیء Summary Zoom Frame دریافت می‌کند.

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