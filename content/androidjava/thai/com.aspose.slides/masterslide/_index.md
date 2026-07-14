---
title: MasterSlide
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึง master slide ในการนำเสนอ.
type: docs
url: /th/com.aspose.slides/masterslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

แสดงถึง master slide ในการนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของ master slide |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | สร้าง master slide ใหม่จาก slide ปัจจุบัน โดยใช้ธีมภายนอกและนำ master slide ที่สร้างไปใช้กับสไลด์ที่ขึ้นอยู่ทั้งหมด |
| [getTitleStyle()](#getTitleStyle--) | คืนค่าสไตล์ของข้อความหัวเรื่อง |
| [getBodyStyle()](#getBodyStyle--) | คืนค่าสไตล์ของข้อความเนื้อหา |
| [getOtherStyle()](#getOtherStyle--) | คืนค่าสไตล์ของข้อความอื่น |
| [getLayoutSlides()](#getLayoutSlides--) | คืนค่าคอลเลกชันของ layout slide ลูกสำหรับ master slide นี้ |
| [getPreserve()](#getPreserve--) | กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาถูกลบหรือไม่ |
| [setPreserve(boolean value)](#setPreserve-boolean-) | กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาถูกลบหรือไม่ |
| [getDependingSlides()](#getDependingSlides--) | คืนค่าอาเรย์ของสไลด์ทั้งหมดที่ขึ้นอยู่กับ master slide นี้ |
| [hasDependingSlides()](#hasDependingSlides--) | คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับ master slide นี้ |
| [getThemeManager()](#getThemeManager--) | คืนค่า theme manager |
| [getName()](#getName--) | คืนค่าหรือกำหนดชื่อของ master slide |
| [setName(String value)](#setName-java.lang.String-) | คืนค่าหรือกำหนดชื่อของ master slide |
| [getShowMasterShapes()](#getShowMasterShapes--) | กำหนดว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่ |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | กำหนดว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่ |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าคอลเลกชันของ drawing guides สำหรับ master slide |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของ master slide. อ่านอย่างเดียว [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**คืนค่า:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

สร้าง master slide ใหม่จาก slide ปัจจุบัน โดยใช้ธีมภายนอกและนำ master slide ที่สร้างไปใช้กับสไลด์ที่ขึ้นอยู่ทั้งหมด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ธีมภายนอก (.thmx) |

**คืนค่า:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide ที่มีธีมใหม่

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

คืนค่าคอลเลกชันของ layout slide ลูกสำหรับ master slide นี้. อ่านอย่างเดียว [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

คุณสามารถเข้าถึง API ทางเลือกสำหรับการเพิ่ม/แทรก/ลบ/ทำสำเนา layout slides ได้โดยใช้คุณสมบัติ ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides))

**คืนค่า:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาถูกลบหรือไม่. หมายเหตุ: Aspose.Slides จะไม่ลบ master ที่ไม่ได้ใช้ใด ๆ ด้วยตัวเอง, หากต้องการลบ master ที่ไม่ได้ใช้จริง ๆ ให้เรียก [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาถูกลบหรือไม่. หมายเหตุ: Aspose.Slides จะไม่ลบ master ที่ไม่ได้ใช้ใด ๆ ด้วยตัวเอง, หากต้องการลบ master ที่ไม่ได้ใช้จริง ๆ ให้เรียก [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

คืนค่าอาเรย์ของสไลด์ทั้งหมดที่ขึ้นอยู่กับ master slide นี้

**คืนค่า:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับ master slide นี้. อ่านอย่างเดียว boolean.

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

คืนค่าหรือกำหนดชื่อของ master slide. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

คืนค่าหรือกำหนดชื่อของ master slide. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

กำหนดว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. สำหรับ master slide เองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

กำหนดว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. สำหรับ master slide เองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

คืนค่าคอลเลกชันของ drawing guides สำหรับ master slide. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // เพิ่ม drawing guide แนวตั้งใหม่ที่ด้านขวาของศูนย์กลางสไลด์
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)