---
title: MasterNotesSlide
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นสไลด์มาสเตอร์สำหรับโน้ต.
type: docs
url: /th/com.aspose.slides/masternotesslide/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

แสดงสไลด์มาสเตอร์สำหรับโน้ต.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์โน้ตมาสเตอร์. |
| [getThemeManager()](#getThemeManager--) | คืนค่า theme manager. |
| [getNotesStyle()](#getNotesStyle--) | คืนค่า style ของข้อความโน้ต. |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าชุดของ drawing guides สำหรับสไลด์โน้ตมาสเตอร์. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่. สำหรับสไลด์มาสเตอร์เองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่. สำหรับสไลด์มาสเตอร์เองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


คืนค่า HeaderFooter manager ของสไลด์โน้ตมาสเตอร์. อ่านเท่านั้น [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**คืนค่า:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


คืนค่า theme manager. อ่านเท่านั้น [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**คืนค่า:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```


คืนค่า style ของข้อความโน้ต. อ่านเท่านั้น [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


คืนค่าชุดของ drawing guides สำหรับสไลด์โน้ตมาสเตอร์. อ่านเท่านั้น [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // เพิ่มไกด์การวาดแนวนอนใหม่ด้านล่างศูนย์กลางสไลด์
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)