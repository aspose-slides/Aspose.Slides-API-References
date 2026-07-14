---
title: IMathNaryOperator
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุวัตถุคณิตศาสตร์แบบ N-ary เช่น Summation และ Integral.
type: docs
url: /th/com.aspose.slides/imathnaryoperator/
---
**อินเทอร์เฟซที่ทำงานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

ระบุวัตถุคณิตศาสตร์แบบ N-ary เช่น Summation และ Integral ประกอบด้วยออปอเรเตอร์, ฐาน (หรือออพแรนด์) และขอบบนและขอบล่างที่เป็นตัวเลือก ตัวอย่างของออปอเรเตอร์แบบ N-ary ได้แก่ Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getSubscript()](#getSubscript--) | ระบุอาร์กิวเมนต์ตัวห้อยที่, ตัวอย่างเช่น ในกรณีของการ integral, กำหนดขอบล่าง |
| [getSuperscript()](#getSuperscript--) | ระบุอาร์กิวเมนต์ตัวเหนือที่, ตัวอย่างเช่น ในกรณีของการ integral, กำหนดขอบบน |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

ระบุอาร์กิวเมนต์ตัวห้อยที่, ตัวอย่างเช่น ในกรณีของการ integral, กำหนดขอบล่าง

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

ระบุอาร์กิวเมนต์ตัวเหนือที่, ตัวอย่างเช่น ในกรณีของการ integral, กำหนดขอบบน

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)