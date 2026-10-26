---
title: SectionZoomFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에서 Section Zoom 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/sectionzoomframe/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**모든 구현된 인터페이스:**  
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)  
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

슬라이드에서 Section Zoom 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Section Zoom 객체가 연결되는 section 객체를 가져오거나 설정합니다. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Section Zoom 객체가 연결되는 section 객체를 가져오거나 설정합니다. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

Section Zoom 객체가 연결되는 section 객체를 가져오거나 설정합니다. 읽기/쓰기 [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> 다음 예제는 대상 섹션을 변경하고 섹션 줌 객체에 대한 새 이미지를 생성하는 방법을 보여줍니다:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**  
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

Section Zoom 객체가 연결되는 section 객체를 가져오거나 설정합니다. 읽기/쓰기 [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> 다음 예제는 대상 섹션을 변경하고 섹션 줌 객체에 대한 새 이미지를 생성하는 방법을 보여줍니다:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |