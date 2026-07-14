---
title: IMathLeftSubSuperscriptElement
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ระบุอ็อบเจ็กต์ Sub-Superscript ซึ่งประกอบด้วยฐาน  และตัวห้อยและตัวใสที่วางอยู่ทางด้านซ้ายของฐาน.
type: docs
url: /th/com.aspose.slides/imathleftsubsuperscriptelement/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLeftSubSuperscriptElement extends IMathElement
```

ระบุวัตถุ Sub-Superscript ซึ่งประกอบด้วยฐานและตัวห้อยและตัวใสที่วางอยู่ทางด้านซ้ายของฐาน.

--------------------

> ```
> Example:
>  
>  IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").setSubSuperscriptOnTheLeft("i", "j");
> ```

## เมธอด

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getSubscript()](#getSubscript--) | ตัวห้อย |
| [getSuperscript()](#getSuperscript--) | ตัวใส |
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
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = leftSubSuperscript.getBase();
> ```


**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
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

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


ตัวใส

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


**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)