---
title: CommonSlideViewProperties
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคุณสมบัติการมองสไลด์ทั่วไป.
type: docs
url: /th/com.aspose.slides/commonslideviewproperties/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

แทนคุณสมบัติการมองสไลด์ทั่วไป

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // สร้างอ็อบเจกต์ Presentation ที่เป็นตัวแทนไฟล์การนำเสนอ
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // กำหนดคุณสมบัติมุมมองของการนำเสนอ
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // ค่าซูมเป็นเปอร์เซ็นต์สำหรับมุมมองสไลด์
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // ค่าซูมเป็นเปอร์เซ็นต์สำหรับมุมมองบันทึกย่อ
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getScale()](#getScale--) | ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์ |
| [setScale(int value)](#setScale-int-) | ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์ |
| [getVariableScale()](#getVariableScale--) | ระบุว่าคอนเทนต์ของมุมมองควรปรับขนาดอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบันที่ดีที่สุด |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | ระบุว่าคอนเทนต์ของมุมมองควรปรับขนาดอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบันที่ดีที่สุด |
| [getDrawingGuides()](#getDrawingGuides--) | ส่งคืนคอลเลกชันของไกด์การวาด |

### getScale() {#getScale--}
```
public final int getScale()
```

ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์. อ่าน/เขียน int.

**ส่งคืน:**
int

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

ระบุอัตราส่วนการขยายมุมมองเป็นเปอร์เซ็นต์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

ระบุว่าคอนเทนต์ของมุมมองควรปรับขนาดอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบันที่ดีที่สุด. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

ระบุว่าคอนเทนต์ของมุมมองควรปรับขนาดอัตโนมัติเพื่อให้พอดีกับขนาดหน้าต่างปัจจุบันที่ดีที่สุด. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

ส่งคืนคอลเลกชันของไกด์การวาด. อ่านอย่างเดียว [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // เพิ่มไกด์การวาดแนวตั้งใหม่ทางด้านขวามือของศูนย์สไลด์
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
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