---
title: SectionZoomFrame
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một đối tượng Section Zoom trong một slide.
type: docs
url: /vi/com.aspose.slides/sectionzoomframe/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Biểu thị một đối tượng Section Zoom trong một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Lấy hoặc đặt đối tượng Section mà đối tượng Section Zoom liên kết tới. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Lấy hoặc đặt đối tượng Section mà đối tượng Section Zoom liên kết tới. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Lấy hoặc đặt đối tượng Section mà đối tượng Section Zoom liên kết tới. Đọc/ghi [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Lấy hoặc đặt đối tượng Section mà đối tượng Section Zoom liên kết tới. Đọc/ghi [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |