---
title: IMasterHandoutSlide
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนสไลด์หลักสำหรับเอกสารสรุป.
type: docs
url: /th/com.aspose.slides/imasterhandoutslide/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

แทนสไลด์หลักสำหรับเอกสารสรุป.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์หลักสำหรับเอกสารสรุป. |
| [getDrawingGuides()](#getDrawingGuides--) | คืนคอลเลกชันของ drawing guides สำหรับสไลด์หลักสำหรับเอกสารสรุป. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


คืนค่า HeaderFooter manager ของสไลด์หลักสำหรับเอกสารสรุป. อ่าน-อย่างเดียว [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**คืนค่า:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


คืนคอลเลกชันของ drawing guides สำหรับสไลด์หลักสำหรับเอกสารสรุป. อ่าน-อย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // เพิ่ม drawing guide แนวนอนใหม่เหนือศูนย์กลางสไลด์
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)