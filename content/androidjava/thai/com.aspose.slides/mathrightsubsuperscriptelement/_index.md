---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: ระบุวัตถุ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวเลขย่อยและตัวเลขยกที่วางอยู่ทางด้านขวาของฐาน.
type: docs
url: /th/com.aspose.slides/mathrightsubsuperscriptelement/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**ทุกอินเทอร์เฟซที่นำไปใช้:**  
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)  
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

ระบุวัตถุ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวเลขย่อยและตัวเลขยกที่วางอยู่ทางด้านขวาของฐาน.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างอินสแตนซ์ใหม่ของคลาส MathRightSubSuperscriptElement |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSubscript()](#getSubscript--) | อากิวเมนต์ Subscript |
| [getSuperscript()](#getSuperscript--) | อากิวเมนต์ Superscript |
| [getAlignScripts()](#getAlignScripts--) | ระบุการจัดแนวของ subscript/superscript. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | ระบุการจัดแนวของ subscript/superscript. |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |

### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

สร้างอินสแตนซ์ใหม่ของคลาส MathRightSubSuperscriptElement

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

อากิวเมนต์ Subscript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

อากิวเมนต์ Superscript

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

ระบุการจัดแนวของ subscript/superscript. เมื่อเป็น true, subscript และ superscript จะจัดแนวแนวนอนต่อกัน เมื่อเป็น false, จะปรับตามรูปทรงของฐาน ค่าเริ่มต้นคือ false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**คืนค่า:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

ระบุการจัดแนวของ subscript/superscript. เมื่อเป็น true, subscript และ superscript จะจัดแนวแนวนอนต่อกัน เมื่อเป็น false, จะปรับตามรูปทรงของฐาน ค่าเริ่มต้นคือ false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับองค์ประกอบลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]