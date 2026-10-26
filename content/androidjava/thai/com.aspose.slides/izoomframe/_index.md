---
title: IZoomFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นอ็อบเจ็กต์ Slide Zoom ในสไลด์.
type: docs
url: /th/com.aspose.slides/izoomframe/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

เป็นอ็อบเจ็กต์ Slide Zoom ในสไลด์.
## เมธอด

| Method | Description |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | ดึงหรือกำหนดอ็อบเจ็กต์สไลด์ที่อ็อบเจ็กต์ Slide Zoom เชื่อมโยงถึง |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | ดึงหรือกำหนดอ็อบเจ็กต์สไลด์ที่อ็อบเจ็กต์ Slide Zoom เชื่อมโยงถึง |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

ดึงหรือกำหนดอ็อบเจ็กต์สไลด์ที่อ็อบเจ็กต์ Slide Zoom เชื่อมโยงถึง. อ่าน/เขียน [ISlide](../../com.aspose.slides/islide).

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
public abstract void setTargetSlide(ISlide value)
```

ดึงหรือกำหนดอ็อบเจ็กต์สไลด์ที่อ็อบเจ็กต์ Slide Zoom เชื่อมโยงถึง. อ่าน/เขียน [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> ตัวอย่างต่อไปนี้สาธิตการเปลี่ยนสไลด์เป้าหมายและสร้างภาพใหม่สำหรับอ็อบเจ็กต์ Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |