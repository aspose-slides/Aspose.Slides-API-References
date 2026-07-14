---
title: InkTrace
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของออบเจกต์ Trace.
type: docs
url: /th/com.aspose.slides/inktrace/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInkTrace](../../com.aspose.slides/iinktrace)
```
public class InkTrace implements IInkTrace
```

เป็นตัวแทนของออบเจกต์ Trace. องค์ประกอบ Trace ใช้เพื่อบันทึกข้อมูลที่ดิจิไทเซอร์จับได้. มันมีลำดับของจุดที่เข้ารหัสตามสเปคที่ให้โดยออบเจกต์ InkTraceFormat.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBrush()](#getBrush--) | รับ Brush สำหรับ IInkLine [IInkBrush](../../com.aspose.slides/iinkbrush) อ่านอย่างเดียว. |
| [getPoints()](#getPoints--) | รับจุดสำหรับ IInkLine android.graphics.PointF อ่านอย่างเดียว. |

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
public final PointF[] getPoints()
```

รับจุดสำหรับ IInkLine android.graphics.PointF อ่านอย่างเดียว.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      android.graphics.PointF[] points = traces[0].getPoints();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
android.graphics.PointF[]