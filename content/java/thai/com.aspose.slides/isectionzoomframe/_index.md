---
title: ISectionZoomFrame
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ Java
description: แสดงถึงอ็อบเจกต์ Section Zoom ในสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/isectionzoomframe/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

แสดงถึงอ็อบเจกต์ Section Zoom ในสไลด์หนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | รับหรือกำหนดวัตถุส่วนที่ออปเจกต์ Section Zoom เชื่อมโยงกับ |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | รับหรือกำหนดวัตถุส่วนที่ออปเจกต์ Section Zoom เชื่อมโยงกับ |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


รับหรือกำหนดวัตถุส่วนที่ออปเจกต์ Section Zoom เชื่อมโยงกับ. อ่าน/เขียน [ISection](../../com.aspose.slides/isection).

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

**คืนค่า:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


รับหรือกำหนดวัตถุส่วนที่ออปเจกต์ Section Zoom เชื่อมโยงกับ. อ่าน/เขียน [ISection](../../com.aspose.slides/isection).

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |