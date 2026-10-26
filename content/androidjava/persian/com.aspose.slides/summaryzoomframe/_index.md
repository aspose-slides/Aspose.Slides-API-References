---
title: SummaryZoomFrame
second_title: مرجع API جاوا Aspose.Slides برای اندروید
description: یک شیء Summary Zoom را در یک اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/summaryzoomframe/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

یک شیء Summary Zoom را در یک اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getLayout()](#getLayout--) | چیدمان بخش‌های Summary Zoom را در فریم دریافت می‌کند. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) را برای شیء Summary Zoom Frame دریافت می‌کند. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


چیدمان بخش‌های Summary Zoom را در فریم دریافت می‌کند. مقدار پیش‌فرض GridLayout است.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگرداندن:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) را برای شیء Summary Zoom Frame دریافت می‌کند.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگرداندن:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)