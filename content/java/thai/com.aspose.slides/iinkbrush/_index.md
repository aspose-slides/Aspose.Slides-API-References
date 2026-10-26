---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: แสดงถึงแปรงร่างเส้น.
type: docs
url: /th/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

แสดงถึงแปรงร่างเส้น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColor()](#getColor--) | รับหรือกำหนดสีแปรงสำหรับเส้น. |
| [setColor(Color value)](#setColor-java.awt.Color-) | รับหรือกำหนดสีแปรงสำหรับเส้น. |
| [getSize()](#getSize--) | รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นจุด. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | รับหรือกำหนดขนาดแปรงสำหรับเส้นเป็นจุด. |
| [getInkEffect()](#getInkEffect--) | รับประเภทเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดรูปแบบการแสดงผลของเส้นหมึก. |

### getColor() {#getColor--}
```
public abstract Color getColor()
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
public abstract void setColor(Color value)
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
public abstract Dimension2D getSize()
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
public abstract void setSize(Dimension2D value)
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
public abstract int getInkEffect()
```


รับประเภทเอฟเฟกต์หมึก (เช่น Galaxy, Gold, Silver) ที่กำหนดรูปแบบการแสดงผลของเส้นหมึก ค่าจะถูกแยกวิเคราะห์จากคุณสมบัติแปรง "inkEffects" หากไม่มีเอฟเฟกต์ที่รู้จักระบุไว้, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) จะถูกส่งคืน.

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