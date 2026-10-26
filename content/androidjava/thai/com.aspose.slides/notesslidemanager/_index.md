---
title: NotesSlideManager
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: ผู้จัดการสไลด์โน้ต.
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

ผู้จัดการสไลด์โน้ต.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์พรีเซนเทชัน
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // เพิ่มโน้ตให้กับสไลด์แรก
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // บันทึกพรีเซนเทชันลงดิสก์
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์พรีเซนเทชัน
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // ลบโน้ตของสไลด์แรก
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // บันทึกพรีเซนเทชันลงดิสก์
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | ส่งคืนสไลด์โน้ตสำหรับสไลด์ปัจจุบัน. |
| [addNotesSlide()](#addNotesSlide--) | ส่งคืนสไลด์โน้ตสำหรับสไลด์ปัจจุบัน ถ้ายังไม่มีจะสร้างขึ้นใหม่. |
| [removeNotesSlide()](#removeNotesSlide--) | ลบสไลด์โน้ตของสไลด์ปัจจุบัน. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


ส่งคืนสไลด์โน้ตสำหรับสไลด์ปัจจุบัน. ส่งคืนค่า null หากสไลด์ไม่มีสไลด์โน้ต. อ่านอย่างเดียว [INotesSlide](../../com.aspose.slides/inotesslide).

**คืนค่า:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


ส่งคืนสไลด์โน้ตสำหรับสไลด์ปัจจุบัน ถ้ายังไม่มีจะสร้างขึ้นใหม่.

**คืนค่า:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) สำหรับสไลด์นี้.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


ลบสไลด์โน้ตของสไลด์ปัจจุบัน.