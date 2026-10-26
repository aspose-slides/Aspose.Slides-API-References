---
title: LayoutSlide
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงสไลด์เลย์เอาต์.
type: docs
url: /th/com.aspose.slides/layoutslide/
---
**Inheritance:**  
การสืบทอด: [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**  
อินเทอร์เฟซที่ทำจริงทั้งหมด:  
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)  
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Represents a layout slide.  
แสดงสไลด์เลย์เอาต์.

## เมธอด

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | คืนค่า HeaderFooter manager ของสไลด์เลย์เอาต์. |
| [getPlaceholderManager()](#getPlaceholderManager--) | คืนค่า placeholder manager ของสไลด์เลย์เอาต์. |
| [getMasterSlide()](#getMasterSlide--) | คืนค่า หรือกำหนด master slide สำหรับเลย์เอาต์. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | คืนค่า หรือกำหนด master slide สำหรับเลย์เอาต์. |
| [remove()](#remove--) | ลบเลย์เอาต์ออกจากงานนำเสนอ. |
| [getThemeManager()](#getThemeManager--) | คืนค่า overriding theme manager. |
| [getLayoutType()](#getLayoutType--) | คืนค่า layout type ของสไลด์เลย์เอาต์นี้. |
| [getDependingSlides()](#getDependingSlides--) | คืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์เลย์เอาต์นี้. |
| [hasDependingSlides()](#hasDependingSlides--) | คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์เลย์เอาต์นี้. |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. |
| [getDrawingGuides()](#getDrawingGuides--) | คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์เลย์เอาต์. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

คืนค่า HeaderFooter manager ของสไลด์เลย์เอาต์. อ่านอย่างเดียว [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**คืนค่า:**  
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)

### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

คืนค่า placeholder manager ของสไลด์เลย์เอาต์. อ่านอย่างเดียว [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**คืนค่า:**  
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)

### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

คืนค่า หรือกำหนด master slide สำหรับเลย์เอาต์. อ่าน/เขียน [IMasterSlide](../../com.aspose.slides/imasterslide).

**คืนค่า:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)

### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

คืนค่า หรือกำหนด master slide สำหรับเลย์เอาต์. อ่าน/เขียน [IMasterSlide](../../com.aspose.slides/imasterslide).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```

ลบเลย์เอาต์ออกจากงานนำเสนอ.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

คืนค่า overriding theme manager. อ่านอย่างเดียว [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**คืนค่า:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

คืนค่า layout type ของสไลด์เลย์เอาต์นี้. อ่านอย่างเดียว [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**คืนค่า:**  
byte

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

คืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์เลย์เอาต์นี้.

**คืนค่า:**  
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์เลย์เอาต์นี้. อ่านอย่างเดียว  boolean .

**คืนค่า:**  
boolean

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน  boolean .

**คืนค่า:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน  boolean .

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

คืนค่าคอลเลกชันของ drawing guides สำหรับสไลด์เลย์เอาต์. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // เพิ่มเส้นแนวตั้งใหม่ไปทางซ้ายของจุดศูนย์ของสไลด์
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)