---
title: SummaryZoomFrame
second_title: Aspose.Slides for Java API 레퍼런스
description: 슬라이드에 있는 Summary Zoom 개체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/summaryzoomframe/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**모든 구현된 인터페이스:**  
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)  
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

슬라이드에 있는 Summary Zoom 개체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLayout()](#getLayout--) | 프레임의 Summary Zoom 섹션 레이아웃을 가져옵니다. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Summary Zoom Frame 개체에 대한 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)을 가져옵니다. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

프레임의 Summary Zoom 섹션 레이아웃을 가져옵니다. 기본값은 GridLayout입니다.

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

**반환:**  
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Summary Zoom Frame 개체에 대한 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)을 가져옵니다.

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

**반환:**  
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)