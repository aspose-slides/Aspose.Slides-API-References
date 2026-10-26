---
title: Ink
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นวัตถุหมึกบนสไลด์.
type: docs
url: /th/com.aspose.slides/ink/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

แสดงวัตถุหมึกบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTraces()](#getTraces--) | ดึงข้อมูลร่างทั้งหมดที่อยู่ในองค์ประกอบ IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | ดึงคอลเลกชันของรูปภาพที่กำหนดเองที่ใช้จำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


ดึงข้อมูลร่างทั้งหมดที่อยู่ในองค์ประกอบ IInk [IInkTrace](../../com.aspose.slides/iinktrace). อ่านอย่างเดียว.

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
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```


ดึงคอลเลกชันของรูปภาพที่กำหนดเองที่ใช้จำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก. รูปภาพเหล่านี้จะถูกใช้เมื่อเรนเดอร์หมึกด้วยค่า [InkEffectType](../../com.aspose.slides/inkeffecttype) เฉพาะ, เช่น Galaxy, Rainbow, เป็นต้น. โดยการจัดเตรียมรูปภาพของคุณเอง, คุณสามารถควบคุมการแสดงผลของแต่ละเอฟเฟกต์หมึกได้.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

คุณสมบัตินี้อนุญาตให้แทนที่เทกเจอร์เอฟเฟกต์หมึกเริ่มต้นด้วยเทกเจอร์ที่ผู้ใช้กำหนดเอง, ซึ่งมีประโยชน์โดยเฉพาะเมื่อทรัพยากรเริ่มต้นถูกจำกัดโดยลิขสิทธิ์หรือไม่พร้อมใช้งานในระหว่างการทำงาน. แต่ละรายการในพจนานุกรมจะต้องเชื่อมโยงค่าที่เป็น [InkEffectType](../../com.aspose.slides/inkeffecttype) กับอ็อบเจ็กต์ [IImage](../../com.aspose.slides/iimage) ที่สอดคล้อง (เช่น Bitmap, หรืออินเทอร์เฟซภาพของ Aspose).

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>