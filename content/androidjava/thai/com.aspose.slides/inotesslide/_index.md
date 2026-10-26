---
title: INotesSlide
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงสไลด์บันทึกย่อยในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/inotesslide/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

แสดงสไลด์บันทึกย่อยในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์บันทึกย่อย. |
| [getNotesTextFrame()](#getNotesTextFrame--) | คืนค่า TextFrame ที่มีข้อความบันทึกย่อยหากมี. |
| [getParentSlide()](#getParentSlide--) | คืนค่า ParentSlide อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


คืนค่า HeaderFooter manager ของสไลด์บันทึกย่อย. อ่านอย่างเดียว [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**คืนค่า:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


คืนค่า TextFrame ที่มีข้อความบันทึกย่อยหากมี. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


คืนค่า ParentSlide อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**  
[ISlide](../../com.aspose.slides/islide)