---
title: MasterSlide
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของสไลด์หลักในงานนำเสนอ
type: docs
url: /th/com.aspose.slides/masterslide/
---
**การสืบทอด:** [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

แทนสไลด์หลักในงานนำเสนอ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์หลัก. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | สร้างสไลด์หลักใหม่จากสไลด์ปัจจุบัน, นำธีมภายนอกไปใช้กับสไลด์นี้และนำสไลด์หลักที่สร้างไปใช้กับสไลด์ที่พึ่งพาทั้งหมด. |
| [getTitleStyle()](#getTitleStyle--) | คืนค่าสไตล์ของข้อความหัวเรื่อง. |
| [getBodyStyle()](#getBodyStyle--) | คืนค่าสไตล์ของข้อความเนื้อหา. |
| [getOtherStyle()](#getOtherStyle--) | คืนค่าสไตล์ของข้อความอื่น. |
| [getLayoutSlides()](#getLayoutSlides--) | คืนคอลเลกชันของสไลด์เค้าโครงย่อยสำหรับสไลด์หลักนี้. |
| [getPreserve()](#getPreserve--) | กำหนดว่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบหรือไม่เมื่อสไลด์ทั้งหมดที่ตามหลังมาสเตอร์นั้นถูกลบ. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | กำหนดว่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบหรือไม่เมื่อสไลด์ทั้งหมดที่ตามหลังมาสเตอร์นั้นถูกลบ. |
| [getDependingSlides()](#getDependingSlides--) | คืนค่าอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์หลักนี้. |
| [hasDependingSlides()](#hasDependingSlides--) | คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์หลักนี้. |
| [getThemeManager()](#getThemeManager--) | คืนค่า theme manager. |
| [getName()](#getName--) | คืนค่า หรือ ตั้งชื่อของสไลด์หลัก. |
| [setName(String value)](#setName-java.lang.String-) | คืนค่า หรือ ตั้งชื่อของสไลด์หลัก. |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบนสไลด์หลักควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบนสไลด์หลักควรแสดงบนสไลด์หรือไม่. |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์หลัก. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์หลัก. อ่านอย่างเดียว [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**คืนค่า:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

สร้างสไลด์หลักใหม่จากสไลด์ปัจจุบัน, นำธีมภายนอกไปใช้กับสไลด์นี้และนำสไลด์หลักที่สร้างไปใช้กับสไลด์ที่พึ่งพาทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ธีมภายนอก (.thmx). |

**คืนค่า:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide ที่มีธีมใหม่.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

คืนค่าสไตล์ของข้อความหัวเรื่อง. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

คืนค่าสไตล์ของข้อความเนื้อหา. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

คืนค่าสไตล์ของข้อความอื่น. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

คืนคอลเลกชันของสไลด์เค้าโครงย่อยสำหรับสไลด์หลักนี้. อ่านอย่างเดียว [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

คุณสามารถเข้าถึง API ทางเลือกสำหรับการเพิ่ม/แทรก/ลบ/ทำสำเนาสไลด์เค้าโครงโดยใช้คุณสมบัติ ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) ได้

**คืนค่า:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

กำหนดว่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบหรือไม่เมื่อสไลด์ทั้งหมดที่ตามหลังมาสเตอร์นั้นถูกลบ. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้ใด ๆ ด้วยตนเอง, เพื่อทำการลบมาสเตอร์ที่ไม่ได้ใช้จริงให้เรียก [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) อ่าน/เขียน boolean .

**คืนค่า:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

กำหนดว่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบหรือไม่เมื่อสไลด์ทั้งหมดที่ตามหลังมาสเตอร์นั้นถูกลบ. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้ใด ๆ ด้วยตนเอง, เพื่อทำการลบมาสเตอร์ที่ไม่ได้ใช้จริงให้เรียก [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) อ่าน/เขียน boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

คืนค่าอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์หลักนี้.

**คืนค่า:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์หลักนี้. อ่านอย่างเดียว boolean .

**คืนค่า:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

คืนค่า theme manager. อ่านอย่างเดียว [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**คืนค่า:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

คืนค่า หรือ ตั้งชื่อของสไลด์หลัก. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

คืนค่า หรือ ตั้งชื่อของสไลด์หลัก. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

ระบุว่ารูปร่างบนสไลด์หลักควรแสดงบนสไลด์หรือไม่. สำหรับสไลด์หลักเองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean .

**คืนค่า:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

ระบุว่ารูปร่างบนสไลด์หลักควรแสดงบนสไลด์หรือไม่. สำหรับสไลด์หลักเองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์หลัก. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // เพิ่มแนวทางการวาดใหม่ในแนวตั้งทางด้านขวาของศูนย์กลางสไลด์
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)