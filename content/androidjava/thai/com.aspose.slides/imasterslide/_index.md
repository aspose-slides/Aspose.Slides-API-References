---
title: IMasterSlide
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นสไลด์หลักในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/imasterslide/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

เป็นสไลด์หลักในงานนำเสนอ.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์หลัก. |
| [getTitleStyle()](#getTitleStyle--) | ส่งคืนสไตล์ของข้อความหัวเรื่อง. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | สร้างสไลด์หลักใหม่จากสไลด์ปัจจุบัน โดยใช้ธีมภายนอกและนำสไลด์หลักที่สร้างไปใช้กับสไลด์ที่พึ่งพาทั้งหมด. |
| [getBodyStyle()](#getBodyStyle--) | ส่งคืนสไตล์ของข้อความเนื้อหา. |
| [getOtherStyle()](#getOtherStyle--) | ส่งคืนสไตล์ของข้อความอื่น. |
| [getLayoutSlides()](#getLayoutSlides--) | ส่งคืนคอลเลกชันของสไลด์เลเอาต์ย่อยสำหรับสไลด์หลักนี้. |
| [getPreserve()](#getPreserve--) | กำหนดว่าค่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาถูกลบหรือไม่. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | กำหนดว่าค่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาถูกลบหรือไม่. |
| [hasDependingSlides()](#hasDependingSlides--) | ส่งคืนค่า true หากมีสไลด์ที่พึ่งพามาสเตอร์สไลด์นี้อย่างน้อยหนึ่งสไลด์. |
| [getDependingSlides()](#getDependingSlides--) | ส่งคืนอาร์เรย์ที่มีสไลด์ทั้งหมดที่พึ่งพามาสเตอร์สไลด์นี้. |
| [getDrawingGuides()](#getDrawingGuides--) | ส่งคืนคอลเลกชันของแนวทางการวาดสำหรับสไลด์หลัก. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

ส่งคืนผู้จัดการ HeaderFooter ของสไลด์หลัก. อ่านอย่างเดียว [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**ส่งคืน:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

ส่งคืนสไตล์ของข้อความหัวเรื่อง. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**ส่งคืน:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

สร้างสไลด์หลักใหม่จากสไลด์ปัจจุบัน โดยใช้ธีมภายนอกและนำสไลด์หลักที่สร้างไปใช้กับสไลด์ที่พึ่งพาทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ธีมภายนอก (.thmx). |

**ส่งคืน:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide ที่มีธีมใหม่

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

ส่งคืนสไตล์ของข้อความเนื้อหา. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**ส่งคืน:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

ส่งคืนสไตล์ของข้อความอื่น. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**ส่งคืน:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

ส่งคืนคอลเลกชันของสไลด์เลเอาต์ย่อยสำหรับสไลด์หลักนี้. อ่านอย่างเดียว [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

คุณสามารถเข้าถึง API ทางเลือกสำหรับการเพิ่ม/แทรก/ลบ/คัดลอกสไลด์เลเอาต์โดยใช้คุณสมบัติ ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) .

**ส่งคืน:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

กำหนดว่าค่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาถูกลบหรือไม่. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้ใด ๆ ด้วยตัวเอง; เพื่อทำการลบมาสเตอร์ที่ไม่ได้ใช้จริงให้เรียก [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) อ่าน/เขียน boolean.

**ส่งคืน:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

กำหนดว่าค่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาถูกลบหรือไม่. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้ใด ๆ ด้วยตัวเอง; เพื่อทำการลบมาสเตอร์ที่ไม่ได้ใช้จริงให้เรียก [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

ส่งคืนค่า true หากมีสไลด์ที่พึ่งพามาสเตอร์สไลด์นี้อย่างน้อยหนึ่งสไลด์. อ่านอย่างเดียว boolean.

**ส่งคืน:**
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

ส่งคืนอาร์เรย์ที่มีสไลด์ทั้งหมดที่พึ่งพามาสเตอร์สไลด์นี้.

**ส่งคืน:**
com.aspose.slides.ISlide[] - อาร์เรย์ของ [ISlide](../../com.aspose.slides/islide), ที่พึ่งพามาสเตอร์สไลด์นี้

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

ส่งคืนคอลเลกชันของแนวทางการวาดสำหรับสไลด์หลัก. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // เพิ่มแนวทางการวาดแนวตั้งใหม่ทางด้านขวาของศูนย์สไลด์
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)