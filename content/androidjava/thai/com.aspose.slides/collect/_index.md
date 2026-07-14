---
title: Collect
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นกลุ่มของเมธอดที่มุ่งหมายเพื่อรวบรวมวัตถุโมเดลประเภทต่าง ๆ จาก .
type: docs
url: /th/com.aspose.slides/collect/
---
**การสืบทอด:**  
java.lang.Object  
```
public class Collect
```

เป็นกลุ่มของเมธอดที่มุ่งหมายเพื่อรวบรวมวัตถุโมเดลประเภทต่าง ๆ จาก [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... เปลี่ยนการจัดรูปแบบของรูปร่างหรือคุณสมบัติอื่นๆ
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Collect()](#Collect--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | รวบรวมอินสแตนซ์ทั้งหมดของ [Shape](../../com.aspose.slides/shape) ใน [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

รวบรวมอินสแตนซ์ทั้งหมดของ [Shape](../../com.aspose.slides/shape) ใน [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // หากรูปร่างเป็น AutoShape ให้เพิ่มเส้นขอบสีดำแบบทึบ
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | การนำเสนอที่ใช้รวบรวมรูปร่าง |

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - คอลเลกชันของรูปร่างทั้งหมดที่อยู่ในการนำเสนอ