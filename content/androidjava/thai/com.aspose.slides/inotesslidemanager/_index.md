---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Notes slide manager.
type: docs
url: /th/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

ผู้จัดการสไลด์บันทึกย่อ.
## เมธอด

| Method | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | คืนสไลด์บันทึกย่อสำหรับสไลด์ปัจจุบัน. |
| [addNotesSlide()](#addNotesSlide--) | คืนสไลด์บันทึกย่อสำหรับสไลด์ปัจจุบัน, สร้างสไลด์ใหม่หากไม่มี. |
| [removeNotesSlide()](#removeNotesSlide--) | ลบสไลด์บันทึกย่อของสไลด์ปัจจุบัน. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


คืนสไลด์บันทึกย่อสำหรับสไลด์ปัจจุบัน. คืนค่า null หากสไลด์ไม่มีสไลด์บันทึกย่อ. อ่านอย่างเดียว [INotesSlide](../../com.aspose.slides/inotesslide).

**คืนค่า:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


คืนสไลด์บันทึกย่อสำหรับสไลด์ปัจจุบัน, สร้างสไลด์ใหม่หากไม่มี.

**คืนค่า:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) สำหรับสไลด์นี้.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


ลบสไลด์บันทึกย่อของสไลด์ปัจจุบัน.