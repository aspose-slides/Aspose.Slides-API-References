---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Java API Reference
description: แสดงคุณสมบัติการแสดงสไลด์ทั่วไป.
type: docs
url: /th/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

แทนคุณสมบัติการแสดงสไลด์ทั่วไป.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getScale()](#getScale--) | ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์. |
| [setScale(int value)](#setScale-int-) | ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์. |
| [getVariableScale()](#getVariableScale--) | ระบุว่าข้อมูลการมองควรปรับสเกลโดยอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบันที่สุด. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | ระบุว่าข้อมูลการมองควรปรับสเกลโดยอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบันที่สุด. |
| [getDrawingGuides()](#getDrawingGuides--) | ส่งคืนคอลเลกชันของไกด์การวาด. |

### getScale() {#getScale--}
```
public abstract int getScale()
```

ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์. อ่าน/เขียน int.

**ส่งคืน:**
int

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

ระบุว่าข้อมูลการมองควรปรับสเกลโดยอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบันที่สุด. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

ระบุว่าข้อมูลการมองควรปรับสเกลโดยอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบันที่สุด. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

ส่งคืนคอลเลกชันของไกด์การวาด. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // เพิ่มไกด์การวาดแนวตั้งใหม่ไปทางขวาของศูนย์สไลด์
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // เพิ่มไกด์การวาดแนวนอนใหม่ด้านล่างศูนย์สไลด์
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ส่งคืน:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)