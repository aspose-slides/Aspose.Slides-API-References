---
title: IZoomFrame
second_title: Tham khảo API Aspose.Slides cho Java
description: Biểu diễn một đối tượng Slide Zoom trong một slide.
type: docs
url: /vi/com.aspose.slides/izoomframe/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Biểu diễn một đối tượng Slide Zoom trong một slide.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Lấy hoặc đặt đối tượng slide mà đối tượng Slide Zoom liên kết tới. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Lấy hoặc đặt đối tượng slide mà đối tượng Slide Zoom liên kết tới. |
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

**Kết quả trả về:**
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