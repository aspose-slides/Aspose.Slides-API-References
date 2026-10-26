---
title: Ink
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนวัตถุหมึกบนสไลด์
type: docs
url: /th/com.aspose.slides/ink/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

แทนวัตถุหมึกบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTraces()](#getTraces--) | ดึง trace ทั้งหมดที่อยู่ใน IInk element [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | ดึงคอลเลกชันของภาพที่กำหนดเองที่ใช้เพื่อจำลองเอฟเฟกต์สำหรับแปรงหมึก. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


ดึง trace ทั้งหมดที่อยู่ใน IInk element [IInkTrace](../../com.aspose.slides/iinktrace). อ่านอย่างเดียว.

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


ดึงคอลเลกชันของภาพที่กำหนดเองที่ใช้เพื่อจำลองเอฟเฟกต์สำหรับแปรงหมึก. ภาพเหล่านี้จะถูกใช้เมื่อเรนเดอร์หมึกด้วยค่า [InkEffectType](../../com.aspose.slides/inkeffecttype) เฉพาะ เช่น Galaxy, Rainbow เป็นต้น. โดยการให้ภาพของคุณเอง คุณสามารถควบคุมลักษณะการแสดงของแต่ละเอฟเฟกต์หมึกได้.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

คุณสมบัตินี้อนุญาตให้แทนที่พื้นผิวเอฟเฟกต์หมึกเริ่มต้นด้วยพื้นผิวที่ผู้ใช้กำหนด ซึ่งเป็นประโยชน์เป็นพิเศษเมื่อทรัพยากรเริ่มต้นถูกจำกัดโดยลิขสิทธิ์หรือไม่สามารถใช้งานได้ในระหว่างทำงาน. รายการแต่ละรายการในพจนานุกรมต้องเชื่อมโยงค่า [InkEffectType](../../com.aspose.slides/inkeffecttype) กับออบเจกต์ [IImage](../../com.aspose.slides/iimage) ที่สอดคล้องกัน (เช่น Bitmap หรืออินเทอร์เฟซรูปภาพของ Aspose).

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>