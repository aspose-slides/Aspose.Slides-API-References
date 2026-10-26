---
title: IZoomFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một đối tượng Slide Zoom trong một slide.
type: docs
url: /vi/com.aspose.slides/izoomframe/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Đại diện cho một đối tượng Slide Zoom trong một slide.
## Methods

| Method | Description |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Gets or sets the slide object that the Slide Zoom object links to. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Gets or sets the slide object that the Slide Zoom object links to. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
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
public abstract void setTargetSlide(ISlide value)
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