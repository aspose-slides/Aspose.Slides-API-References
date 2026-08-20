---
title: NotesSlideManager
second_title: Aspose.Slides สำหรับ Java API Reference
description: ผู้จัดการสไลด์บันทึกหมายเหตุ.
type: docs
url: /th/com.aspose.slides/notesslidemanager/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

ผู้จัดการสไลด์บันทึกหมายเหตุ.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // สร้างออบเจกต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // เพิ่มหมายเหตุในสไลด์แรก
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // บันทึกงานนำเสนอลงดิสก์
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // สร้างออบเจกต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // ลบหมายเหตุของสไลด์แรก
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // บันทึกงานนำเสนอลงดิสก์
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | ส่งคืนสไลด์บันทึกหมายเหตุของสไลด์ปัจจุบัน. |
| [addNotesSlide()](#addNotesSlide--) | ส่งคืนสไลด์บันทึกหมายเหตุของสไลด์ปัจจุบัน หากไม่มีจะสร้างใหม่. |
| [removeNotesSlide()](#removeNotesSlide--) | ลบสไลด์บันทึกหมายเหตุของสไลด์ปัจจุบัน. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


ส่งคืนสไลด์บันทึกหมายเหตุของสไลด์ปัจจุบัน หากสไลด์ไม่มีสไลด์บันทึกหมายเหตุจะส่งค่า null. อ่านอย่างเดียว [INotesSlide](../../com.aspose.slides/inotesslide).

**ส่งคืน:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


ส่งคืนสไลด์บันทึกหมายเหตุของสไลด์ปัจจุบัน หากไม่มีจะสร้างใหม่.

**ส่งคืน:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) for this slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


ลบสไลด์บันทึกหมายเหตุของสไลด์ปัจจุบัน.