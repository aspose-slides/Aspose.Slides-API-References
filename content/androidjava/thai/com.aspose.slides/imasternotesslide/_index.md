---
title: IMasterNotesSlide
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงสไลด์มาสเตอร์สำหรับโน้ต.
type: docs
url: /th/com.aspose.slides/imasternotesslide/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

แสดงสไลด์มาสเตอร์สำหรับโน้ต.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนตัวจัดการ HeaderFooter ของสไลด์โน้ตมาสเตอร์. |
| [getNotesStyle()](#getNotesStyle--) | ส่งคืนสไตล์ของข้อความโน้ต. |
| [getDrawingGuides()](#getDrawingGuides--) | ส่งคืนคอลเลกชันของไกด์การวาดสำหรับสไลด์โน้ตมาสเตอร์. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


ส่งคืนตัวจัดการ HeaderFooter ของสไลด์โน้ตมาสเตอร์. อ่านอย่างเดียว [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**ส่งคืน:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


ส่งคืนสไตล์ของข้อความโน้ต. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**ส่งคืน:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


ส่งคืนคอลเลกชันของไกด์การวาดสำหรับสไลด์โน้ตมาสเตอร์. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // เพิ่มไกด์การวาดแนวนอนใหม่ด้านล่างศูนย์ของสไลด์
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งคืน:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)