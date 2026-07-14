---
title: MathRadical
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: ระบุฟังก์ชันรัศมีที่ประกอบด้วยฐานและระดับที่เป็นตัวเลือก.
type: docs
url: /th/com.aspose.slides/mathradical/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

ระบุฟังก์ชันรัศมี ซึ่งประกอบด้วยฐานและระดับที่เป็นตัวเลือก ตัวอย่างของวัตถุรัศมีคือ \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathRadical |
## เมธอด

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนท์ฐาน |
| [getDegree()](#getDegree--) | อาร์กิวเมนท์ระดับ |
| [getHideDegree()](#getHideDegree--) | ซ่อนระดับ เมื่อค่าเป็นจริง ระดับจะไม่แสดง เช่น \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | ซ่อนระดับ เมื่อค่าเป็นจริง ระดับจะไม่แสดง เช่น \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
| [getChildren()](#getChildren--) | รับองค์ประกอบย่อย
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
| Parameter | Type | Description |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ฐาน |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | ระดับ |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนท์ฐาน

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

อาร์กิวเมนท์ระดับ

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

ซ่อนระดับ เมื่อค่าเป็นจริง ระดับจะไม่แสดง เช่น \\u221a\\ud835\\udc65

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

ซ่อนระดับ เมื่อค่าเป็นจริง ระดับจะไม่แสดง เช่น \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
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

รับองค์ประกอบย่อย

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]