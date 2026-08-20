---
title: MathRadical
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: ระบุฟังก์ชันรากที่ประกอบด้วยฐานและดีกรีที่เป็นตัวเลือก.
type: docs
url: /th/com.aspose.slides/mathradical/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

ระบุฟังก์ชันรากที่ประกอบด้วยฐานและดีกรีที่เป็นตัวเลือก ตัวอย่างของอ็อบเจ็กต์รากคือ \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathRadical. |
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getDegree()](#getDegree--) | อาร์กิวเมนต์ดีกรี |
| [getHideDegree()](#getHideDegree--) | ซ่อนดีกรี เมื่อเป็น true ดีกรีจะไม่แสดง เช่น \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | ซ่อนดีกรี เมื่อเป็น true ดีกรีจะไม่แสดง เช่น \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ฐาน |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | ดีกรี |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


อาร์กิวเมนต์ดีกรี

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


ซ่อนดีกรี เมื่อเป็น true ดีกรีจะไม่แสดง เช่น \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**ผลลัพธ์:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


ซ่อนดีกรี เมื่อเป็น true ดีกรีจะไม่แสดง เช่น \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


คุณสมบัติตัวอักษรควบคุม

**ผลลัพธ์:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


ดึงองค์ประกอบลูก

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]