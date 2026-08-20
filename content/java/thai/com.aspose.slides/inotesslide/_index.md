---
title: INotesSlide
second_title: Aspose.Slides สำหรับ Java – เอกสารอ้างอิง API
description: เป็นตัวแทนของสไลด์บันทึกในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/inotesslide/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)  
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

แสดงสไลด์บันทึกในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์บันทึก. |
| [getNotesTextFrame()](#getNotesTextFrame--) | ส่งคืน TextFrame พร้อมข้อความบันทึกหากมี. |
| [getParentSlide()](#getParentSlide--) | ส่งคืน ParentSlide อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

ส่งคืนผู้จัดการ HeaderFooter ของสไลด์บันทึก. อ่านอย่างเดียว [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**ส่งคืน:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

ส่งคืน TextFrame พร้อมข้อความบันทึกหากมี. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**ส่งคืน:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

ส่งคืน ParentSlide อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**ส่งคืน:**
[ISlide](../../com.aspose.slides/islide)