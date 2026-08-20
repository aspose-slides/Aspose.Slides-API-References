---
title: ISummaryZoomSection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل كائن Summary Zoom Section في إطار Summary Zoom.
type: docs
url: /ar/com.aspose.slides/isummaryzoomsection/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

يمثل كائن Summary Zoom Section في إطار Summary Zoom.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTitle()](#getTitle--) | يرجع عنوان النص لكائن Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يرجع عنوان النص لكائن Summary Zoom Section. |
| [getDescription()](#getDescription--) | يرجع الوصف النصي لكائن Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | يرجع الوصف النصي لكائن Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

يرجع عنوان النص لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**القيمة المرجعة:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

يرجع الوصف النصي لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**القيمة المرجعة:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```

يرجع الوصف النصي لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |