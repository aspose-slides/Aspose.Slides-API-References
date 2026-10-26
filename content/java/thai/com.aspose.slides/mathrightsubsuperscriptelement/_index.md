---
title: MathRightSubSuperscriptElement
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุอ็อบเจ็กต์ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวล่างและตัวบนที่วางอยู่ทางขวาของฐาน.
type: docs
url: /th/com.aspose.slides/mathrightsubsuperscriptelement/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)  
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

ระบุออบเจ็กต์ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวล่างและตัวบนที่วางไว้ทางขวาของฐาน.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```
## คอนสตรักเตอร์

| Constructor | คำอธิบาย |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathRightSubSuperscriptElement. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSubscript()](#getSubscript--) | อาร์กิวเมนต์ Subscript |
| [getSuperscript()](#getSuperscript--) | อาร์กิวเมนต์ Superscript |
| [getAlignScripts()](#getAlignScripts--) | ระบุการจัดแนวของ subscript/superscript. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | ระบุการจัดแนวของ subscript/superscript. |
| [getChildren()](#getChildren--) | รับ elements ลูก |

### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathRightSubSuperscriptElement.

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

อาร์กิวเมนต์ Subscript

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

**ผลลัพธ์:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

อาร์กิวเมนต์ Superscript

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

**ผลลัพธ์:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

ระบุการจัดแนวของ subscript/superscript. เมื่อเป็น true, subscript และ superscript จะถูกจัดแนวตามแนวนอนต่อกัน. เมื่อเป็น false, จะถูกเคอร์นตามรูปทรงของ base. ค่าปริยายคือ false.

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

**ผลลัพธ์:**  
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

ระบุการจัดแนวของ subscript/superscript. เมื่อเป็น true, subscript และ superscript จะถูกจัดแนวตามแนวนอนต่อกัน. เมื่อเป็น false, จะถูกเคอร์นตามรูปทรงของ base. ค่าปริยายคือ false.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับ elements ลูก

**ผลลัพธ์:**  
com.aspose.slides.IMathElement[]