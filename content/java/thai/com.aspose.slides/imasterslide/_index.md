---
title: IMasterSlide
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงสไลด์แม่ในงานนำเสนอ
type: docs
url: /th/com.aspose.slides/imasterslide/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

แทนสไลด์แม่ในงานนำเสนอหนึ่งๆ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของ master slide. |
| [getTitleStyle()](#getTitleStyle--) | คืนค่าสไตล์ของข้อความหัวเรื่อง. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | สร้างสไลด์แม่ใหม่โดยอิงจากสไลด์ปัจจุบัน, นำธีมภายนอกไปใช้กับสไลด์นั้นและนำสไลด์แม่ที่สร้างขึ้นไปใช้กับสไลด์ที่พึ่งพาทั้งหมด. |
| [getBodyStyle()](#getBodyStyle--) | คืนค่าสไตล์ของข้อความส่วนเนื้อหา. |
| [getOtherStyle()](#getOtherStyle--) | คืนค่าสไตล์ของข้อความอื่น. |
| [getLayoutSlides()](#getLayoutSlides--) | คืนค่าคอลเลกชันของสไลด์เค้าโครงย่อยสำหรับสไลด์แม่นี้. |
| [getPreserve()](#getPreserve--) | กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาหลังจากมาสเตอร์นั้นถูกลบหรือไม่. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาหลังจากมาสเตอร์นั้นถูกลบหรือไม่. |
| [hasDependingSlides()](#hasDependingSlides--) | คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่พึ่งพาสไลด์แม่นี้. |
| [getDependingSlides()](#getDependingSlides--) | คืนค่าอาเรย์ที่มีสไลด์ทั้งหมดที่พึ่งพาสไลด์แม่นี้. |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าคอลเลกชันของแนวทางการวาดสำหรับสไลด์แม่. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


คืนค่า HeaderFooter manager ของ master slide. อ่านอย่างเดียว [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**คืนค่า:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


คืนค่าสไตล์ของข้อความหัวเรื่อง. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


สร้างสไลด์แม่ใหม่โดยอิงจากสไลด์ปัจจุบัน, นำธีมภายนอกไปใช้กับสไลด์นั้นและนำสไลด์แม่ที่สร้างขึ้นไปใช้กับสไลด์ที่พึ่งพาทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fname | java.lang.String | เส้นทางไปยังไฟล์ธีมภายนอก (.thmx). |

**คืนค่า:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide ที่มีธีมใหม่.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


คืนค่าสไตล์ของข้อความส่วนเนื้อหา. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


คืนค่าสไตล์ของข้อความอื่น. อ่านอย่างเดียว [ITextStyle](../../com.aspose.slides/itextstyle).

**คืนค่า:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


คืนค่าคอลเลกชันของสไลด์เค้าโครงย่อยสำหรับสไลด์แม่นี้. อ่านอย่างเดียว [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

คุณสามารถเข้าถึง API ทางเลือกสำหรับการเพิ่ม/แทรก/ลบ/สำเนาสไลด์เค้าโครงโดยใช้คุณสมบัติ ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**คืนค่า:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาหลังจากมาสเตอร์นั้นถูกลบหรือไม่. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้ใดๆ ด้วยตัวเอง, เพื่อที่จะลบมาสเตอร์ที่ไม่ได้ใช้จริงๆ ให้เรียก [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาหลังจากมาสเตอร์นั้นถูกลบหรือไม่. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้ใดๆ ด้วยตัวเอง, เพื่อที่จะลบมาสเตอร์ที่ไม่ได้ใช้จริงๆ ให้เรียก [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่พึ่งพาสไลด์แม่นี้. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


คืนค่าอาเรย์ที่มีสไลด์ทั้งหมดที่พึ่งพาสไลด์แม่นี้.

**คืนค่า:**
com.aspose.slides.ISlide[] - อาเรย์ของ [ISlide](../../com.aspose.slides/islide) ที่พึ่งพาสไลด์แม่นี้
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


คืนค่าคอลเลกชันของแนวทางการวาดสำหรับสไลด์แม่. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // เพิ่มแนวทางการวาดแนวตั้งใหม่ที่ด้านขวาของศูนย์สไลด์
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)