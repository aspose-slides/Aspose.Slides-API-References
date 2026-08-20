---
title: InkBrush
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของวัตถุ inkBrush.
type: docs
url: /th/com.aspose.slides/inkbrush/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

เป็นตัวแทนของวัตถุ inkBrush.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColor()](#getColor--) | รับหรือกำหนดสีแปรงสำหรับเส้น. |
| [setColor(Color value)](#setColor-java.awt.Color-) | รับหรือกำหนดสีแปรงสำหรับเส้น. |
| [getSize()](#getSize--) | รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นหน่วยจุด. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นหน่วยจุด. |
| [getInkEffect()](#getInkEffect--) | รับประเภทเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดรูปแบบการแสดงของเส้นหมึก. |
### getColor() {#getColor--}
```
public final Color getColor()
```

รับหรือกำหนดสีแปรงสำหรับเส้น.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

รับหรือกำหนดสีแปรงสำหรับเส้น.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นหน่วยจุด.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นหน่วยจุด.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

รับประเภทเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดรูปแบบการแสดงของเส้นหมึก. ค่าถูกแยกวิเคราะห์จากคุณสมบัติแปรง "inkEffects". หากไม่มีเอฟเฟกต์ที่รับรู้ระบุ, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) จะถูกคืนค่า.

**คืนค่า:**
int