---
title: IMasterHandoutSlide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นสไลด์มาสเตอร์สำหรับเอกสารประกอบการสอน.
type: docs
url: /th/com.aspose.slides/imasterhandoutslide/
---
**ส่วนต่อประสานทั้งหมดที่ใช้งาน:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

เป็นสไลด์มาสเตอร์สำหรับเอกสารประกอบการสอน.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์มาสเตอร์สำหรับเอกสารประกอบการสอน. |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าชุดของ drawing guides สำหรับสไลด์มาสเตอร์ของเอกสารประกอบการสอน. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์มาสเตอร์สำหรับเอกสารประกอบการสอน. อ่านอย่างเดียว [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**คืนค่า:**  
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

คืนค่าชุดของ drawing guides สำหรับสไลด์มาสเตอร์ของเอกสารประกอบการสอน. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // เพิ่มแนววาดแนวนอนใหม่เหนือกึ่งกลางสไลด์
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)