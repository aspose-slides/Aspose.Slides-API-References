---
title: IZoomFrame
second_title: Aspose.Slides for Java API 레퍼런스
description: 슬라이드에 있는 Slide Zoom 개체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/izoomframe/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

슬라이드에 있는 Slide Zoom 개체를 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom 개체가 연결되는 슬라이드 개체를 가져오거나 설정합니다. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom 개체가 연결되는 슬라이드 개체를 가져오거나 설정합니다. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Slide Zoom 개체가 연결되는 슬라이드 개체를 가져오거나 설정합니다. 읽기/쓰기 [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**반환:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Slide Zoom 개체가 연결되는 슬라이드 개체를 가져오거나 설정합니다. 읽기/쓰기 [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> 다음 예제는 대상 슬라이드를 변경하고 Slide Zoom 개체에 대한 새 이미지를 생성하는 방법을 보여줍니다:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |