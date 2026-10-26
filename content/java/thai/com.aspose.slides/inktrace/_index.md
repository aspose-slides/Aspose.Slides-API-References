---
title: InkTrace
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นออบเจกต์ Trace ที่ใช้เพื่อบันทึกข้อมูล.
type: docs
url: /th/com.aspose.slides/inktrace/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

เป็นออบเจกต์ Trace ที่ใช้เพื่อบันทึกข้อมูลที่จับได้จากดิจิไทเซอร์ ประกอบด้วยลำดับของจุดที่เข้ารหัสตามสเปคที่กำหนดโดยออบเจกต์ InkTraceFormat
## เมธอด

| Method | Description |
| --- | --- |
| [getBrush()](#getBrush--) | รับ Brush สำหรับ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) อ่านอย่างเดียว. |
| [getPoints()](#getPoints--) | รับจุดสำหรับ IInkLine java.awt.geom.Point2D.Float อ่านอย่างเดียว. |
### getBrush() {#getBrush--}
```
public final IInkBrush getBrush()
```

รับ Brush สำหรับ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) อ่านอย่างเดียว.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IInkBrush](../../com.aspose.slides/iinkbrush)
### getPoints() {#getPoints--}
```
public final Point2D.Float[] getPoints()
```

รับจุดสำหรับ IInkLine java.awt.geom.Point2D.Float อ่านอย่างเดียว.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      Point2D.Float[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
java.awt.geom.Point2D.Float[]