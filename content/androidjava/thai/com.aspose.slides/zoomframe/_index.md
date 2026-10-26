---
title: ZoomFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงอ็อบเจกต์ Slide Zoom ในสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/zoomframe/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

แสดงถึงอ็อบเจกต์ Slide Zoom ในสไลด์หนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | รับหรือกำหนดอ็อบเจกต์สไลด์ที่อ็อบเจกต์ Slide Zoom เชื่อมโยงไปยัง |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | รับหรือกำหนดอ็อบเจกต์สไลด์ที่อ็อบเจกต์ Slide Zoom เชื่อมโยงไปยัง |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


รับหรือกำหนดอ็อบเจกต์สไลด์ที่อ็อบเจกต์ Slide Zoom เชื่อมโยงไปยัง อ่าน/เขียน [ISlide](../../com.aspose.slides/islide).

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


รับหรือกำหนดอ็อบเจกต์สไลด์ที่อ็อบเจกต์ Slide Zoom เชื่อมโยงไปยัง อ่าน/เขียน [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> ตัวอย่างต่อไปแสดงการเปลี่ยนแปลงสไลด์เป้าหมายและสร้างภาพใหม่สำหรับอ็อบเจกต์ Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |