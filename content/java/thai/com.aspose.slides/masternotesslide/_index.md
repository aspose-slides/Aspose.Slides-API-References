---
title: MasterNotesSlide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นสไลด์มาสเตอร์สำหรับบันทึกย่อ.
type: docs
url: /th/com.aspose.slides/masternotesslide/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)  
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

เป็นสไลด์มาสเตอร์สำหรับบันทึกย่อ.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปทรงบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่ |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปทรงบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่ |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์บันทึกย่อมาสเตอร์ |
| [getThemeManager()](#getThemeManager--) | คืนค่า theme manager |
| [getNotesStyle()](#getNotesStyle--) | คืนค่า style ของข้อความบันทึกย่อ |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์บันทึกย่อมาสเตอร์ |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

ระบุว่ารูปทรงบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์มาสเตอร์เองคุณสมบัตินี้จะคืนค่า false เสมอ อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

ระบุว่ารูปทรงบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์มาสเตอร์เองคุณสมบัตินี้จะคืนค่า false เสมอ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์บันทึกย่อมาสเตอร์ อ่านอย่างเดียว [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**คืนค่า:**  
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

คืนค่า theme manager. อ่านอย่างเดียว [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**คืนค่า:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

คืนค่า style ของข้อความบันทึกย่อ. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์บันทึกย่อมาสเตอร์. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // เพิ่มแนวทางการวาดแนวนอนใหม่ใต้ศูนย์กลางของสไลด์
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)