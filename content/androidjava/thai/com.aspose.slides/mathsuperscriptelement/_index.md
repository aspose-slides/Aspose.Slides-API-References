---
title: MathSuperscriptElement
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุวัตถุซุปเปอร์สคริปต์ที่ประกอบด้วยฐานและซุปเปอร์สคริปต์ขนาดลดลงที่วางอยู่เหนือและทางขวา
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

กำหนดวัตถุซุปเปอร์สคริปต์ ซึ่งประกอบด้วยฐานและซุปเปอร์สคริปต์ขนาดลดลงที่วางอยู่เหนือและทางขวา

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
>  ```
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างอินสแตนซ์ใหม่ของคลาส MathSuperscriptElement. |
## วิธีการ

| Method | Description |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | ซุปเปอร์สคริปต์ |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathSuperscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
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
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

ดึงองค์ประกอบลูก

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]