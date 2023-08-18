---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Java API Reference
description: Represents a Summary Zoom frame in a slide.
type: docs
weight: 1049
url: /com.aspose.slides/isummaryzoomframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Represents a Summary Zoom frame in a slide.
## Methods

| Method | Description |
| --- | --- |
| [getLayout()](#getLayout--) | Gets layout of Summary Zoom Sections in the frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Gets [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) for the Summary Zoom Frame object. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Gets layout of Summary Zoom Sections in the frame. Default value is GridLayout.

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

**Returns:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Gets [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) for the Summary Zoom Frame object.

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

**Returns:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
