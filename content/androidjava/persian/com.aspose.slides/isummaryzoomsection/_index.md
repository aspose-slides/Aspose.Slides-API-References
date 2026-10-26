---
title: ISummaryZoomSection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایندهٔ شیء Summary Zoom Section در یک فریم Summary Zoom است.
type: docs
url: /fa/com.aspose.slides/isummaryzoomsection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

نمایش‌دهندهٔ شیء Summary Zoom Section در یک فریم Summary Zoom.

## متدها

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | عنوان متنی شیء Summary Zoom Section را برمی‌گرداند. |
| [setTitle(String value)](#setTitle-java.lang.String-) | عنوان متنی شیء Summary Zoom Section را برمی‌گرداند. |
| [getDescription()](#getDescription--) | توضیح متنی شیء Summary Zoom Section را برمی‌گرداند. |
| [setDescription(String value)](#setDescription-java.lang.String-) | توضیح متنی شیء Summary Zoom Section را برمی‌گرداند. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

عنوان متنی شیء Summary Zoom Section را برمی‌گرداند.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**بازگرداندن:**  
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

توضیح متنی شیء Summary Zoom Section را برمی‌گرداند.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**بازگرداندن:**  
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |