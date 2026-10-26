---
title: Collect
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ Java
description: แทนกลุ่มของเมธอดที่มีจุดมุ่งหมายเพื่อรวบรวมอ็อบเจกต์โมเดลประเภทต่าง ๆ จาก .
type: docs
url: /th/com.aspose.slides/collect/
---
**การสืบทอด:**
java.lang.Object
```
public class Collect
```

แทนกลุ่มของเมธอดที่มีวัตถุประสงค์เพื่อรวบรวมอ็อบเจกต์โมเดลประเภทต่าง ๆ จาก [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... เปลี่ยนการจัดรูปแบบของรูปร่างหรือคุณสมบัติอื่น ๆ
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
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
>          // ถ้า shape เป็น AutoShape ให้เพิ่มเส้นขอบสีดำแบบทึบ
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
| pres | [Presentation](../../com.aspose.slides/presentation) | งานนำเสนอที่ใช้ในการรวบรวมรูป |

**ค่าที่ส่งกลับ:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - คอลเลกชันของรูปทั้งหมดที่อยู่ในงานนำเสนอ