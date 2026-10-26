---
title: SummaryZoomSection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل كائن قسم التكبير الملخص داخل إطار التكبير الملخص.
type: docs
url: /ar/com.aspose.slides/summaryzoomsection/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

يمثل كائن قسم التكبير الملخص داخل إطار التكبير الملخص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTitle()](#getTitle--) | تُرجِع عنوان النص لكائن قسم التكبير الملخص. |
| [setTitle(String value)](#setTitle-java.lang.String-) | تُرجِع عنوان النص لكائن قسم التكبير الملخص. |
| [getDescription()](#getDescription--) | تُرجِع وصف النص لكائن قسم التكبير الملخص. |
| [setDescription(String value)](#setDescription-java.lang.String-) | تُرجِع وصف النص لكائن قسم التكبير الملخص. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

تُرجِع عنوان النص لكائن قسم التكبير الملخص.

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

تُرجِع عنوان النص لكائن قسم التكبير الملخص.

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
public final String getDescription()
```

تُرجِع وصف النص لكائن قسم التكبير الملخص.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**الإرجاع:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```

تُرجِع وصف النص لكائن قسم التكبير الملخص.

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