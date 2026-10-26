---
title: SummaryZoomSection
second_title: Aspose.Slides لـ Java دليل واجهة برمجة التطبيقات
description: يمثل كائن Summary Zoom Section داخل إطار Summary Zoom.
type: docs
url: /ar/com.aspose.slides/summaryzoomsection/
---
**الإرث:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

يمثل كائن Summary Zoom Section في إطار Summary Zoom.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTitle()](#getTitle--) | يرجع عنوان النص لكائن Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يرجع عنوان النص لكائن Summary Zoom Section. |
| [getDescription()](#getDescription--) | يرجع وصف النص لكائن Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | يرجع وصف النص لكائن Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


يرجع عنوان النص لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**الإرجاع:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


يرجع عنوان النص لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


يرجع وصف النص لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
>  ```


**الإرجاع:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


يرجع وصف النص لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
>  ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |