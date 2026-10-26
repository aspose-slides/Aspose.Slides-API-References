---
title: MathSubscriptElement
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุอ็อบเจ็กต์ subscript ซึ่งประกอบด้วยฐานและ subscript ขนาดลดลงที่วางอยู่ด้านล่างและด้านขวา.
type: docs
url: /th/com.aspose.slides/mathsubscriptelement/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

ระบุวัตถุ subscript ซึ่งประกอบด้วยฐานและ subscript ขนาดลดลงที่วางอยู่ด้านล่างและด้านขวา.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างอินสแตนซ์ใหม่ของคลาส MathSubscriptElement |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSubscript()](#getSubscript--) | ตัวห้อย |
| [getChildren()](#getChildren--) | รับอิลิเมนต์ลูก |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathSubscriptElement

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

ตัวห้อย

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับอิลิเมนต์ลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]