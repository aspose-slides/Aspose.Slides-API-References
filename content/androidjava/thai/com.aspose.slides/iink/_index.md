---
title: IInk
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นอ็อบเจกต์หมึกบนสไลด์.
type: docs
url: /th/com.aspose.slides/iink/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

เป็นอ็อบเจกต์หมึกบนสไลด์  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTraces()](#getTraces--) | ดึงร่องรอยทั้งหมดที่อยู่ในองค์ประกอบ IInk [IInkTrace](../../com.aspose.slides/iinktrace). |

### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

ดึงร่องรอยทั้งหมดที่อยู่ในองค์ประกอบ IInk [IInkTrace](../../com.aspose.slides/iinktrace). อ่านอย่างเดียว.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**  
com.aspose.slides.IInkTrace[]