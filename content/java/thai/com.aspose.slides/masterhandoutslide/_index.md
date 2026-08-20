---
title: MasterHandoutSlide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นสไลด์หลักสำหรับสำเนาแบบพิมพ์
type: docs
url: /th/com.aspose.slides/masterhandoutslide/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

แสดงสไลด์หลักสำหรับสำเนาแบบพิมพ์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบนสไลด์หลักควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบนสไลด์หลักควรแสดงบนสไลด์หรือไม่. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์สำเนาแบบพิมพ์หลัก. |
| [getThemeManager()](#getThemeManager--) | คืนค่า theme manager. |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์สำเนาแบบพิมพ์หลัก. |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

ระบุว่ารูปร่างบนสไลด์หลักควรแสดงบนสไลด์หรือไม่. สำหรับสไลด์หลักคุณสมบัตินี้จะคืนค่าเป็น false เสมอ. บูลีน อ่าน/เขียน

**คืนค่า:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

ระบุว่ารูปร่างบนสไลด์หลักควรแสดงบนสไลด์หรือไม่. สำหรับสไลด์หลักคุณสมบัตินี้จะคืนค่าเป็น false เสมอ. บูลีน อ่าน/เขียน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์สำเนาแบบพิมพ์หลัก. อ่านอย่างเดียว [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**คืนค่า:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

คืนค่า theme manager. อ่านอย่างเดียว [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**คืนค่า:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์สำเนาแบบพิมพ์หลัก. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // เพิ่มแนววาดแนวนอนใหม่เหนือกึ่งกลางสไลด์
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)