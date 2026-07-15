---
title: ZoomFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một đối tượng Slide Zoom trong một slide.
type: docs
url: /vi/com.aspose.slides/zoomframe/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Tất cả giao diện được triển khai:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Đại diện cho một đối tượng Slide Zoom trong một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Lấy hoặc đặt đối tượng slide mà đối tượng Slide Zoom liên kết tới. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Lấy hoặc đặt đối tượng slide mà đối tượng Slide Zoom liên kết tới. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Lấy hoặc đặt đối tượng slide mà đối tượng Slide Zoom liên kết tới. Đọc/ghi [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Lấy hoặc đặt đối tượng slide mà đối tượng Slide Zoom liên kết tới. Đọc/ghi [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |