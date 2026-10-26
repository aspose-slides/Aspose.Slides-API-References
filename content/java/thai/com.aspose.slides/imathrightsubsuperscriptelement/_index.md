---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ระบุวัตถุ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวห้อยและตัวบนที่วางทางขวาของฐาน
type: docs
url: /th/com.aspose.slides/imathrightsubsuperscriptelement/
---
**อินเตอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

ระบุวัตถุ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวห้อยและตัวบนที่วางทางขวาของฐาน

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getSubscript()](#getSubscript--) | อาร์กิวเมนต์ตัวห้อย |
| [getSuperscript()](#getSuperscript--) | อาร์กิวเมนต์ตัวบน |
| [getAlignScripts()](#getAlignScripts--) | ระบุการจัดตำแหน่งของตัวห้อย/ตัวบน |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | ระบุการจัดตำแหน่งของตัวห้อย/ตัวบน |
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


อาร์กิวเมนต์ตัวห้อย

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


อาร์กิวเมนต์ตัวบน

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


ระบุการจัดตำแหน่งของตัวห้อย/ตัวบน เมื่อเป็นจริง ตัวห้อยและตัวบนจะจัดแนวนอนสัมพันธ์กัน เมื่อเป็นเท็จ จะปรับให้เข้ากับรูปทรงของฐาน ค่าเริ่มต้นคือ false

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


ระบุการจัดตำแหน่งของตัวห้อย/ตัวบน เมื่อเป็นจริง ตัวห้อยและตัวบนจะจัดแนวนอนสัมพันธ์กัน เมื่อเป็นเท็จ จะปรับให้เข้ากับรูปทรงของฐาน ค่าเริ่มต้นคือ false

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