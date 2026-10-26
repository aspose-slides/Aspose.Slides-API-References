---
title: MasterHandoutSlide
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: เป็นตัวแทนของสไลด์มาสเตอร์สำหรับเอกสารประกอบ.
type: docs
url: /th/com.aspose.slides/masterhandoutslide/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)  
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

เป็นตัวแทนของสไลด์มาสเตอร์สำหรับเอกสารประกอบ.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่ |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่ |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์มาสเตอร์สำหรับเอกสารประกอบ |
| [getThemeManager()](#getThemeManager--) | คืนค่า theme manager |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์มาสเตอร์สำหรับเอกสารประกอบ |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์มาสเตอร์เอง property นี้จะคืนค่า false เสมอ อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์มาสเตอร์เอง property นี้จะคืนค่า false เสมอ อ่าน/เขียน boolean.

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์มาสเตอร์สำหรับเอกสารประกอบ อ่านอย่างเดียว [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**คืนค่า:**  
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

คืนค่า theme manager อ่านอย่างเดียว [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**คืนค่า:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์มาสเตอร์สำหรับเอกสารประกอบ อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // เพิ่มแนวการวาดแนวนอนใหม่เหนือกึ่งกลางสไลด์
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)