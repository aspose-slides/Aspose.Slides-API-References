---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Java API 레퍼런스
description: 슬라이드의 Summary Zoom 프레임을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isummaryzoomframe/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

슬라이드의 Summary Zoom 프레임을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLayout()](#getLayout--) | 프레임에서 Summary Zoom 섹션의 레이아웃을 가져옵니다. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Summary Zoom Frame 객체에 대한 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)를 가져옵니다. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


프레임에서 Summary Zoom 섹션의 레이아웃을 가져옵니다. 기본값은 GridLayout입니다.

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

**반환값:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Summary Zoom Frame 객체에 대한 [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)를 가져옵니다.

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

**반환값:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)