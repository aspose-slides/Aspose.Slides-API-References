---
title: ISectionZoomFrame
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một đối tượng Section Zoom trong một slide.
type: docs
url: /vi/com.aspose.slides/isectionzoomframe/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Biểu diễn một đối tượng Section Zoom trong một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Lấy hoặc đặt đối tượng section mà đối tượng Section Zoom được liên kết tới. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Lấy hoặc đặt đối tượng section mà đối tượng Section Zoom được liên kết tới. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Lấy hoặc đặt đối tượng section mà đối tượng Section Zoom được liên kết tới. Đọc/ghi [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Lấy hoặc đặt đối tượng section mà đối tượng Section Zoom được liên kết tới. Đọc/ghi [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |