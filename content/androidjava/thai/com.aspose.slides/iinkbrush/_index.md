---
title: IInkBrush
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงแปรงรอย
type: docs
url: /th/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

แสดงถึงแปรงรอย
## เมธอด

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | รับหรือกำหนดสีแปรงสำหรับเส้น |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | รับหรือกำหนดสีแปรงสำหรับเส้น |
| [getSize()](#getSize--) | รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นหน่วยจุด |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นหน่วยจุด |
| [getInkEffect()](#getInkEffect--) | ดึงประเภทเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดสไตล์ภาพของลายเส้นหมึก |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

รับหรือกำหนดสีแปรงสำหรับเส้น

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
public abstract void setColor(Integer value)
```

รับหรือกำหนดสีแปรงสำหรับเส้น

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นหน่วยจุด

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
public abstract void setSize(SizeF value)
```

รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นหน่วยจุด

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

ดึงประเภทเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดสไตล์ภาพของลายเส้นหมึก ค่าจะถูกแยกวิเคราะห์จากคุณสมบัติแปรง "inkEffects" หากไม่มีเอฟเฟกต์ที่จดจำได้ใด ๆ จะคืนค่า [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
int