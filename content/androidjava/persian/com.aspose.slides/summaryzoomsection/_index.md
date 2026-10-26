---
title: SummaryZoomSection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شیء Summary Zoom Section را در یک فریم Summary Zoom نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/summaryzoomsection/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

یک شیء Summary Zoom Section را در یک فریم Summary Zoom نشان می‌دهد.
## متدها

| متد | توضیحات |
| --- | --- |
| [getTitle()](#getTitle--) | عنوان متنی شیء Summary Zoom Section را برمی‌گرداند. |
| [setTitle(String value)](#setTitle-java.lang.String-) | عنوان متنی شیء Summary Zoom Section را برمی‌گرداند. |
| [getDescription()](#getDescription--) | توضیح متنی شیء Summary Zoom Section را برمی‌گرداند. |
| [setDescription(String value)](#setDescription-java.lang.String-) | توضیح متنی شیء Summary Zoom Section را برمی‌گرداند. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

عنوان متنی شیء Summary Zoom Section را برمی‌گرداند.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**باز می‌گرداند:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

عنوان متنی شیء Summary Zoom Section را برمی‌گرداند.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```

توضیح متنی شیء Summary Zoom Section را برمی‌گرداند.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**باز می‌گرداند:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```

توضیح متنی شیء Summary Zoom Section را برمی‌گرداند.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | java.lang.String |  |