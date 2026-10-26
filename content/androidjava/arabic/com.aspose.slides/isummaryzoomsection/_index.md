---
title: ISummaryZoomSection
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل كائن Summary Zoom Section داخل إطار Summary Zoom.
type: docs
url: /ar/com.aspose.slides/isummaryzoomsection/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

يمثل كائن Summary Zoom Section داخل إطار Summary Zoom.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTitle()](#getTitle--) | إرجاع عنوان النص لكائن Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | إرجاع عنوان النص لكائن Summary Zoom Section. |
| [getDescription()](#getDescription--) | إرجاع الوصف النصي لكائن Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | إرجاع الوصف النصي لكائن Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

إرجاع عنوان النص لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**القيمة المرجعة:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

إرجاع عنوان النص لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

إرجاع الوصف النصي لكائن Summary Zoom Section.

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

إرجاع الوصف النصي لكائن Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |