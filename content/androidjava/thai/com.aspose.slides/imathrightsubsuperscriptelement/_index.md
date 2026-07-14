---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุอ็อบเจกต์ Sub-Superscript ซึ่งประกอบด้วยฐาน  และตัวห้อยและตัวเอียมที่วางทางขวามือของฐาน.
type: docs
url: /th/com.aspose.slides/imathrightsubsuperscriptelement/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

ระบุอ็อบเจกต์ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวห้อยและตัวเอียมที่วางทางขวามือของฐาน.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getSubscript()](#getSubscript--) | อาร์กิวเมนต์ระดับล่าง |
| [getSuperscript()](#getSuperscript--) | อาร์กิวเมนต์ระดับบน |
| [getAlignScripts()](#getAlignScripts--) | ระบุการจัดตำแหน่งของระดับล่าง/ระดับบน |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | ระบุการจัดตำแหน่งของระดับล่าง/ระดับบน |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


อาร์กิวเมนต์ระดับล่าง

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
public abstract IMathElement getSuperscript()
```


อาร์กิวเมนต์ระดับบน

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
public abstract boolean getAlignScripts()
```


ระบุการจัดตำแหน่งของระดับล่าง/ระดับบน เมื่อเป็นจริง ตัวห้อยและตัวเอียมจะจัดตำแหน่งแนวนอนต่อกัน เมื่อเป็นเท็จ จะจัดตามรูปร่างของฐาน ค่าเริ่มต้นคือเท็จ

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
public abstract void setAlignScripts(boolean value)
```


ระบุการจัดตำแหน่งของระดับล่าง/ระดับบน เมื่อเป็นจริง ตัวห้อยและตัวเอียมจะจัดตำแหน่งแนวนอนต่อกัน เมื่อเป็นเท็จ จะจัดตามรูปร่างของฐาน ค่าเริ่มต้นคือเท็จ

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