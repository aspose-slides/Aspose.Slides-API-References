---
title: SummaryZoomFrame
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a Summary Zoom object in a slide.
type: docs
weight: 530
url: /java/com.aspose.slides/summaryzoomframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Represents a Summary Zoom object in a slide.
## Constructors

| Constructor | Description |
| --- | --- |
| [SummaryZoomFrame(ShapeCollection parentImmediate)](#SummaryZoomFrame-com.aspose.slides.ShapeCollection-) | Creates new SummaryZoomFrame object and initializes properties by default values. |
## Methods

| Method | Description |
| --- | --- |
| [getLayout()](#getLayout--) | Gets layout of Summary Zoom Sections in the frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Gets [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) for the Summary Zoom Frame object. |
### SummaryZoomFrame(ShapeCollection parentImmediate) {#SummaryZoomFrame-com.aspose.slides.ShapeCollection-}
```
 SummaryZoomFrame(ShapeCollection parentImmediate)
```


Creates new SummaryZoomFrame object and initializes properties by default values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [ShapeCollection](../../com.aspose.slides/shapecollection) | Parent object [ShapeCollection](../com.aspose.slides/shapecollection) |

### getLayout() {#getLayout--}
```
public final int getLayout()
```


Gets layout of Summary Zoom Sections in the frame. Default value is GridLayout.

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

**Returns:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Gets [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) for the Summary Zoom Frame object.

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

**Returns:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
