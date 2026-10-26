---
title: ZoomFrame
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: แสดงอ็อบเจ็กต์ Slide Zoom ในสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/zoomframe/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**ส่วนต่อประสานที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)  
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

แสดงอ็อบเจ็กต์ Slide Zoom ในสไลด์หนึ่ง

## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | รับหรือกำหนดวัตถุสไลด์ที่อ็อบเจ็กต์ Slide Zoom เชื่อมโยงไป |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | รับหรือกำหนดวัตถุสไลด์ที่อ็อบเจ็กต์ Slide Zoom เชื่อมโยงไป |

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

รับหรือกำหนดวัตถุสไลด์ที่อ็อบเจ็กต์ Slide Zoom เชื่อมโยงไป. อ่าน/เขียน [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**คืนค่า:**  
[ISlide](../../com.aspose.slides/islide)

### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

รับหรือกำหนดวัตถุสไลด์ที่อ็อบเจ็กต์ Slide Zoom เชื่อมโยงไป. อ่าน/เขียน [ISlide](../../com.aspose.slides/islide).

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