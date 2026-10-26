---
title: IMathNaryOperator
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ระบุวัตถุคณิตศาสตร์ N-ary เช่น ผลรวมและอินทิกรัล.
type: docs
url: /th/com.aspose.slides/imathnaryoperator/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

ระบุวัตถุคณิตศาสตร์ N-ary เช่น ผลรวมและอินทิกรัล ซึ่งประกอบด้วยตัวดำเนินการ ฐาน (หรือออเปอแรนด์) และขีดจำกัดบนและล่างที่เป็นตัวเลือก ตัวอย่างของตัวดำเนินการ N-ary ได้แก่: ผลรวม, ยูเนียน, อินเตอร์เซคชัน, อินทิกรัล

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getSubscript()](#getSubscript--) | ระบุอาร์กิวเมนต์ดัชนีย่อยที่, ตัวอย่างเช่น, ในกรณีของอินทิกรัล, กำหนดขีดจำกัดล่าง |
| [getSuperscript()](#getSuperscript--) | ระบุอาร์กิวเมนต์ดัชนีชั้นบนที่, ตัวอย่างเช่น, ในกรณีของอินทิกรัล, กำหนดขีดจำกัดบน |
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

ระบุอาร์กิวเมนต์ดัชนีย่อยที่, ตัวอย่างเช่น, ในกรณีของอินทิกรัล, กำหนดขีดจำกัดล่าง

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

ระบุอาร์กิวเมนต์ดัชนีชั้นบนที่, ตัวอย่างเช่น, ในกรณีของอินทิกรัล, กำหนดขีดจำกัดบน

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)