---
title: SummaryZoomFrame
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 슬라이드에서 Summary Zoom 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/summaryzoomframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

슬라이드에서 Summary Zoom 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLayout()](#getLayout--) | 프레임에서 Summary Zoom Sections의 레이아웃을 가져옵니다. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Summary Zoom Frame 객체에 대한 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)를 가져옵니다. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

프레임에서 Summary Zoom Sections의 레이아웃을 가져옵니다. 기본값은 GridLayout입니다.

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

**반환값:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Summary Zoom Frame 객체에 대한 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)를 가져옵니다.

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

**반환값:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)