---
title: IZoomFrame
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงออบเจกต์ Slide Zoom ในสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/izoomframe/
---
**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

แสดงออบเจกต์ Slide Zoom ในสไลด์หนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | รับหรือกำหนดวัตถุสไลด์ที่ออบเจกต์ Slide Zoom เชื่อมโยงถึง. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | รับหรือกำหนดวัตถุสไลด์ที่ออบเจกต์ Slide Zoom เชื่อมโยงถึง. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

รับหรือกำหนดวัตถุสไลด์ที่ออบเจกต์ Slide Zoom เชื่อมโยงถึง. อ่าน/เขียน [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISSlide-}
```
public abstract void setTargetSlide(ISlide value)
```

รับหรือกำหนดวัตถุสไลด์ที่ออบเจกต์ Slide Zoom เชื่อมโยงถึง. อ่าน/เขียน [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |