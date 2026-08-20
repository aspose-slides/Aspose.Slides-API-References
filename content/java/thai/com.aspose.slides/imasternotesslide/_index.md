---
title: IMasterNotesSlide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงสไลด์มาสเตอร์สำหรับบันทึกย่อ.
type: docs
url: /th/com.aspose.slides/imasternotesslide/
---
**ส่วนต่อประสานที่ทำไว้ทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

แสดงสไลด์มาสเตอร์สำหรับบันทึกย่อ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์มาสเตอร์โน้ต |
| [getNotesStyle()](#getNotesStyle--) | ส่งคืนสไตล์ของข้อความโน้ต |
| [getDrawingGuides()](#getDrawingGuides--) | ส่งคืนชุดของแนวทางการวาดสำหรับสไลด์มาสเตอร์โน้ต |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


ส่งคืนผู้จัดการ HeaderFooter ของสไลด์มาสเตอร์โน้ต. อ่านอย่างเดียว [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**คืนค่า:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


ส่งคืนสไตล์ของข้อความโน้ต. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


ส่งคืนชุดของแนวทางการวาดสำหรับสไลด์มาสเตอร์โน้ต. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // เพิ่มแนวทางการวาดแนวนอนใหม่ด้านล่างจุดกึ่งกลางของสไลด์
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)