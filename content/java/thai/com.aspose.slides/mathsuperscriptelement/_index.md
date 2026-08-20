---
title: MathSuperscriptElement
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุวัตถุซุปเปอร์สคริปต์ซึ่งประกอบด้วยฐานและซุปเปอร์สคริปต์ขนาดย่อที่วางอยู่เหนือและทางด้านขวา
type: docs
url: /th/com.aspose.slides/mathsuperscriptelement/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

ระบุวัตถุซุปเปอร์สคริปต์ซึ่งประกอบด้วยฐานและซุปเปอร์สคริปต์ขนาดย่อที่วางอยู่เหนือและทางด้านขวา

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathSuperscriptElement |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | ซุปเปอร์สคริปต์ |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathSuperscriptElement

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

ซุปเปอร์สคริปต์

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับองค์ประกอบลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]