---
title: NotesSlide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงสไลด์บันทึกในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/notesslide/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

แสดงถึงสไลด์บันทึกในงานนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์บันทึก |
| [getNotesTextFrame()](#getNotesTextFrame--) | คืนค่า TextFrame ที่มีข้อความของบันทึกหากมี |
| [getThemeManager()](#getThemeManager--) | คืนค่า overriding theme manager |
| [getParentSlide()](#getParentSlide--) | คืนค่า parent slide |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปบน master slide ควรแสดงบนสไลด์หรือไม่ |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปบน master slide ควรแสดงบนสไลด์หรือไม่ |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์บันทึก. อ่านอย่างเดียว [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**คืนค่า:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

คืนค่า TextFrame ที่มีข้อความของบันทึกหากมี. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

คืนค่า overriding theme manager. อ่านอย่างเดียว [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**คืนค่า:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

คืนค่า parent slide. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

ระบุว่ารูปบน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

ระบุว่ารูปบน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |