---
title: ISectionZoomFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นอ็อบเจกต์ Section Zoom ในสไลด์
type: docs
url: /th/com.aspose.slides/isectionzoomframe/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

แสดงอ็อบเจกต์ Section Zoom ในสไลด์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | รับหรือกำหนดอ็อบเจกต์ส่วนที่อ็อบเจกต์ Section Zoom เชื่อมโยงอยู่ |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | รับหรือกำหนดอ็อบเจกต์ส่วนที่อ็อบเจกต์ Section Zoom เชื่อมโยงอยู่ |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

รับหรือกำหนดอ็อบเจกต์ส่วนที่อ็อบเจกต์ Section Zoom เชื่อมโยงอยู่ อ่าน/เขียน [ISection](../../com.aspose.slides/isection)

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

**ค่าที่ส่งคืน:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

รับหรือกำหนดอ็อบเจกต์ส่วนที่อ็อบเจกต์ Section Zoom เชื่อมโยงอยู่ อ่าน/เขียน [ISection](../../com.aspose.slides/isection)

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