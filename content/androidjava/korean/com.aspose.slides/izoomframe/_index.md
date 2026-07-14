---
title: IZoomFrame
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 슬라이드에 있는 Slide Zoom 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/izoomframe/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Represents a Slide Zoom object in a slide.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom 객체가 연결되는 슬라이드 개체를 가져오거나 설정합니다. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom 객체가 연결되는 슬라이드 개체를 가져오거나 설정합니다. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Slide Zoom 객체가 연결되는 슬라이드 개체를 가져오거나 설정합니다. 읽기/쓰기 [ISlide](../../com.aspose.slides/islide).

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

Slide Zoom 객체가 연결되는 슬라이드 개체를 가져오거나 설정합니다. 읽기/쓰기 [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |