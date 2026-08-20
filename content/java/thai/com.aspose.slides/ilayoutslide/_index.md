---
title: ILayoutSlide
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงสไลด์เลย์เอาต์.
type: docs
url: /th/com.aspose.slides/ilayoutslide/
---
**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

แสดงสไลด์แบบเลย์เอาต์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์เลย์เอาต์. |
| [getPlaceholderManager()](#getPlaceholderManager--) | ส่งคืนผู้จัดการ placeholder ของสไลด์เลย์เอาต์. |
| [getMasterSlide()](#getMasterSlide--) | ส่งคืนหรือกำหนดสไลด์แม่สำหรับเลย์เอาต์. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | ส่งคืนหรือกำหนดสไลด์แม่สำหรับเลย์เอาต์. |
| [getLayoutType()](#getLayoutType--) | ส่งคืนประเภทเลย์เอาต์ของสไลด์เลย์เอาต์นี้. |
| [hasDependingSlides()](#hasDependingSlides--) | ส่งคืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่พึ่งพาสไลด์เลย์เอาต์นี้. |
| [getDependingSlides()](#getDependingSlides--) | ส่งคืนอาร์เรย์ที่มีสไลด์ทั้งหมดที่พึ่งพาสไลด์เลย์เอาต์นี้. |
| [remove()](#remove--) | ลบเลย์เอาต์ออกจากการนำเสนอ. |
| [getDrawingGuides()](#getDrawingGuides--) | ส่งคืนคอลเลกชันของ drawing guides สำหรับสไลด์เลย์เอาต์. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


ส่งคืนผู้จัดการ HeaderFooter ของสไลด์เลย์เอาต์. อ่านเท่านั้น [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**คืนค่า:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


ส่งคืนผู้จัดการ placeholder ของสไลด์เลย์เอาต์. อ่านเท่านั้น [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**คืนค่า:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


ส่งคืนหรือกำหนดสไลด์แม่สำหรับเลย์เอาต์. อ่าน/เขียน [IMasterSlide](../../com.aspose.slides/imasterslide).

**คืนค่า:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


ส่งคืนหรือกำหนดสไลด์แม่สำหรับเลย์เอาต์. อ่าน/เขียน [IMasterSlide](../../com.aspose.slides/imasterslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


ส่งคืนประเภทเลย์เอาต์ของสไลด์เลย์เอาต์นี้. อ่านเท่านั้น [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**คืนค่า:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


ส่งคืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่พึ่งพาสไลด์เลย์เอาต์นี้. อ่านเท่านั้น boolean.

**คืนค่า:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


ส่งคืนอาร์เรย์ที่มีสไลด์ทั้งหมดที่พึ่งพาสไลด์เลย์เอาต์นี้.

**คืนค่า:**
com.aspose.slides.ISlide[] - Array with all slides, which depend on this layout slide
### remove() {#remove--}
```
public abstract void remove()
```


ลบเลย์เอาต์ออกจากการนำเสนอ.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


ส่งคืนคอลเลกชันของ drawing guides สำหรับสไลด์เลย์เอาต์. อ่านเท่านั้น [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // เพิ่มไกด์การวาดแนวตั้งใหม่ทางด้านซ้ายของศูนย์กลางสไลด์
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)