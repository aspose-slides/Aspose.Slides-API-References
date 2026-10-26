---
title: IInk
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงอ็อบเจ็กต์หมึกบนสไลด์.
type: docs
url: /th/com.aspose.slides/iink/
---
**ส่วนอินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

แสดงถึงอ็อบเจ็กต์หมึกบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTraces()](#getTraces--) | ดึงรอยทั้งหมดที่อยู่ในองค์ประกอบ IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

ดึงรอยทั้งหมดที่อยู่ในองค์ประกอบ IInk [IInkTrace](../../com.aspose.slides/iinktrace). อ่านได้อย่างเดียว.

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