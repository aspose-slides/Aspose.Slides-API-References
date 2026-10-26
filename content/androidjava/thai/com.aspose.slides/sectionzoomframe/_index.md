---
title: SectionZoomFrame
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงวัตถุ Section Zoom ในสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/sectionzoomframe/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**อินเทอร์เฟซที่ทำทั้งหมด:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

แทนวัตถุ Section Zoom ในสไลด์หนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | รับหรือกำหนดอ็อบเจ็กต์ส่วนที่วัตถุ Section Zoom เชื่อมโยงไป. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | รับหรือกำหนดอ็อบเจ็กต์ส่วนที่วัตถุ Section Zoom เชื่อมโยงไป. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


รับหรือกำหนดอ็อบเจ็กต์ส่วนที่วัตถุ Section Zoom เชื่อมโยงไป. อ่าน/เขียน [ISection](../../com.aspose.slides/isection).

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

**คืนค่า:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


รับหรือกำหนดอ็อบเจ็กต์ส่วนที่วัตถุ Section Zoom เชื่อมโยงไป. อ่าน/เขียน [ISection](../../com.aspose.slides/isection).

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |