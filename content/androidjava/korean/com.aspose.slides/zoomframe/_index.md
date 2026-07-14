---
title: ZoomFrame
second_title: Android용 Aspose.Slides Java API 참조
description: 슬라이드에서 Slide Zoom 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/zoomframe/
---
**상속:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

슬라이드에 있는 Slide Zoom 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom 객체가 연결하는 슬라이드 객체를 가져오거나 설정합니다. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom 객체가 연결하는 슬라이드 객체를 가져오거나 설정합니다. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


Slide Zoom 객체가 연결하는 슬라이드 객체를 가져오거나 설정합니다. 읽기/쓰기 [ISlide](../../com.aspose.slides/islide).

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
public final void setTargetSlide(ISlide value)
```


Slide Zoom 객체가 연결하는 슬라이드 객체를 가져오거나 설정합니다. 읽기/쓰기 [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |