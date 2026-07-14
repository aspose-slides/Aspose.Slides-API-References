---
title: InkBrush
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงวัตถุ inkBrush.
type: docs
url: /th/com.aspose.slides/inkbrush/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

แสดงถึงวัตถุ inkBrush.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColor()](#getColor--) | รับหรือกำหนดสีของแปรงสำหรับเส้น |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | รับหรือกำหนดสีของแปรงสำหรับเส้น |
| [getSize()](#getSize--) | รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นจุด |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นจุด |
| [getInkEffect()](#getInkEffect--) | รับประเภทเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดรูปแบบการแสดงผลของเส้นหมึก |

### getColor() {#getColor--}
```
public final Integer getColor()
```

รับหรือกำหนดสีของแปรงสำหรับเส้น.

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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

รับหรือกำหนดสีของแปรงสำหรับเส้น.

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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นจุด.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```

รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นจุด.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

รับประเภทเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดรูปแบบการแสดงผลของเส้นหมึก. หากไม่มีเอฟเฟกต์ที่รู้จักระบุ, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) จะถูกส่งกลับ.

**คืนค่า:**
int