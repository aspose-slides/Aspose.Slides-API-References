---
title: NotesSlide
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงสไลด์โน้ตในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/notesslide/
---
**สืบทอด:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

แสดงสไลด์โน้ตในงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์โน้ต. |
| [getNotesTextFrame()](#getNotesTextFrame--) | คืนค่า TextFrame ที่มีข้อความโน้ตหากมี. |
| [getThemeManager()](#getThemeManager--) | คืนค่า overriding theme manager. |
| [getParentSlide()](#getParentSlide--) | คืนค่า parent slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | กำหนดว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | กำหนดว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```


คืนค่า HeaderFooter manager ของสไลด์โน้ต. อ่านอย่างเดียว [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**คืนค่า:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```


คืนค่า TextFrame ที่มีข้อความโน้ตหากมี. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

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


กำหนดว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


กำหนดว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |