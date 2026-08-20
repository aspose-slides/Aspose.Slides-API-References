---
title: MathLeftSubSuperscriptElement
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ระบุอ็อบเจกต์ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวห้อยและตัวยกที่วางอยู่ด้านซ้ายของฐาน
type: docs
url: /th/com.aspose.slides/mathleftsubsuperscriptelement/
---
**สืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
```
public final class MathLeftSubSuperscriptElement extends BaseScript implements IMathLeftSubSuperscriptElement
```

ระบุอ็อบเจกต์ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวห้อยและตัวยกที่วางอยู่ทางซ้ายของฐาน

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathLeftSubSuperscriptElement |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSubscript()](#getSubscript--) | ตัวห้อย |
| [getSuperscript()](#getSuperscript--) | ตัวยก |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |

### MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathLeftSubSuperscriptElement

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

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
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = leftSubSuperscript.getSubscript();
> ```

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


ตัวยก

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = leftSubSuperscript.getSuperscript();
> ```

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


รับองค์ประกอบลูก

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]