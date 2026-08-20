---
title: LayoutSlide
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของสไลด์เลเอาต์
type: docs
url: /th/com.aspose.slides/layoutslide/
---
**Inheritance:**  
การสืบทอด: [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**  
อินเทอร์เฟซที่นำไปใช้ทั้งหมด: [com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Represents a layout slide.  
แสดงสไลด์เลเอาต์.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์เลเอต. |
| [getPlaceholderManager()](#getPlaceholderManager--) | ส่งคืนผู้จัดการ placeholder ของสไลด์เลเอต. |
| [getMasterSlide()](#getMasterSlide--) | ส่งคืนหรือกำหนดสไลด์แม่สำหรับเลเอต. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | ส่งคืนหรือกำหนดสไลด์แม่สำหรับเลเอต. |
| [remove()](#remove--) | ลบเลเอตออกจากงานนำเสนอ. |
| [getThemeManager()](#getThemeManager--) | ส่งคืนผู้จัดการธีมที่แทนที่. |
| [getLayoutType()](#getLayoutType--) | ส่งคืนประเภทเลเอตของสไลด์เลเอตนี้. |
| [getDependingSlides()](#getDependingSlides--) | ส่งคืนอาเรย์ที่มีสไลด์ทั้งหมดที่พึ่งพาสไลด์เลเอตนี้. |
| [hasDependingSlides()](#hasDependingSlides--) | ส่งคืน true หากมีสไลด์อย่างน้อยหนึ่งที่พึ่งพาสไลด์เลเอตนี้. |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปทรงบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปทรงบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่. |
| [getDrawingGuides()](#getDrawingGuides--) | ส่งคืนคอลเลกชันของแนวนำทางการวาดสำหรับสไลด์เลเอต. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


ส่งคืนผู้จัดการ HeaderFooter ของสไลด์เลเอต. อ่านอย่างเดียว [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**ส่งคืน:**  
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


ส่งคืนผู้จัดการ placeholder ของสไลด์เลเอต. อ่านอย่างเดียว [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**ส่งคืน:**  
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


ส่งคืนหรือกำหนดสไลด์แม่สำหรับเลเอต. อ่าน/เขียน [IMasterSlide](../../com.aspose.slides/imasterslide).

**ส่งคืน:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


ส่งคืนหรือกำหนดสไลด์แม่สำหรับเลเอต. อ่าน/เขียน [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```


ลบเลเอตออกจากงานนำเสนอ.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


ส่งคืนผู้จัดการธีมที่แทนที่. อ่านอย่างเดียว [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**ส่งคืน:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


ส่งคืนประเภทเลเอตของสไลด์เลเอตนี้. อ่านอย่างเดียว [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**ส่งคืน:**  
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


ส่งคืนอาเรย์ที่มีสไลด์ทั้งหมดที่พึ่งพาสไลด์เลเอตนี้.

**ส่งคืน:**  
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


ส่งคืน true หากมีสไลด์อย่างน้อยหนึ่งที่พึ่งพาสไลด์เลเอตนี้. อ่านอย่างเดียว  boolean .

**ส่งคืน:**  
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


ระบุว่ารูปทรงบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน  boolean .

**ส่งคืน:**  
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


ระบุว่ารูปทรงบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน  boolean .

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


ส่งคืนคอลเลกชันของแนวนำทางการวาดสำหรับสไลด์เลเอต. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // เพิ่มแนวนำทางการวาดแนวตั้งใหม่ทางด้านซ้ายของจุดศูนย์กลางสไลด์
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ส่งคืน:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)