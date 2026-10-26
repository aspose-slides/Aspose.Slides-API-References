---
title: ILayoutSlide
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดงถึงสไลด์เค้าโครง.
type: docs
url: /th/com.aspose.slides/ilayoutslide/
---
**ทั้งหมด Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

แสดงถึงสไลด์เค้าโครง.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์เค้าโครง. |
| [getPlaceholderManager()](#getPlaceholderManager--) | คืนค่า placeholder manager ของสไลด์เค้าโครง. |
| [getMasterSlide()](#getMasterSlide--) | คืนค่า หรือ ตั้งค่า master slide สำหรับเค้าโครง. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | คืนค่า หรือ ตั้งค่า master slide สำหรับเค้าโครง. |
| [getLayoutType()](#getLayoutType--) | คืนค่า layout type ของสไลด์เค้าโครงนี้. |
| [hasDependingSlides()](#hasDependingSlides--) | คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์เค้าโครงนี้. |
| [getDependingSlides()](#getDependingSlides--) | คืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์เค้าโครงนี้. |
| [remove()](#remove--) | ลบเค้าโครงออกจากงานนำเสนอ. |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์เค้าโครง. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์เค้าโครง. อ่านอย่างเดียว [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**คืนค่า:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

คืนค่า placeholder manager ของสไลด์เค้าโครง. อ่านอย่างเดียว [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**คืนค่า:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

คืนค่า หรือ ตั้งค่า master slide สำหรับเค้าโครง. อ่าน/เขียน [IMasterSlide](../../com.aspose.slides/imasterslide).

**คืนค่า:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

คืนค่า หรือ ตั้งค่า master slide สำหรับเค้าโครง. อ่าน/เขียน [IMasterSlide](../../com.aspose.slides/imasterslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

คืนค่า layout type ของสไลด์เค้าโครงนี้. อ่านอย่างเดียว [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**คืนค่า:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์เค้าโครงนี้. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

คืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์เค้าโครงนี้.

**คืนค่า:**
com.aspose.slides.ISlide[] - อาร์เรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์เค้าโครงนี้
### remove() {#remove--}
```
public abstract void remove()
```

ลบเค้าโครงออกจากงานนำเสนอ.
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์เค้าโครง. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // เพิ่มแนวทางการวาดแนวตั้งใหม่ทางซ้ายของจุดศูนย์กลางสไลด์
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)