---
title: MathLimit
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ระบุอ็อบเจ็กต์ Limit ซึ่งประกอบด้วยข้อความบนบรรทัดฐานและข้อความขนาดเล็กที่อยู่เหนือหรือใต้บรรทัดฐานโดยตรง
type: docs
url: /th/com.aspose.slides/mathlimit/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathLimit](../../com.aspose.slides/imathlimit), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathLimit extends MathElementBase implements IMathLimit, IHasControlCharacterProperties
```

ระบุออบเจ็กต์ Limit ซึ่งประกอบด้วยข้อความบนบรรทัดฐานและข้อความขนาดเล็กที่อยู่ด้านบนหรือด้านล่างของมันโดยตรง.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathLimit. |
| [MathLimit(IMathElement baseArg, IMathElement limit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathLimit ด้วยขีดจำกัดล่าง |
## เมธอด

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getLimit()](#getLimit--) | อาร์กิวเมนต์ขีดจำกัด |
| [getUpperLimit()](#getUpperLimit--) | ระบุตำแหน่งขีดจำกัดบนหรือขอบล่าง |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | ระบุตำแหน่งขีดจำกัดบนหรือขอบล่าง |
| [getChildren()](#getChildren--) | ดึงรายการลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathLimit.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"), false);
> ```

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |
| upperLimit | boolean |  |

### MathLimit(IMathElement baseArg, IMathElement limit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLimit(IMathElement baseArg, IMathElement limit)
```


เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathLimit ด้วยขีดจำกัดล่าง

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**ค่าที่คืน:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public final IMathElement getLimit()
```


อาร์กิวเมนต์ขีดจำกัด

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**ค่าที่คืน:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public final boolean getUpperLimit()
```


ระบุตำแหน่งขีดจำกัดบนหรือขอบล่าง

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**ค่าที่คืน:**  
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public final void setUpperLimit(boolean value)
```


ระบุตำแหน่งขีดจำกัดบนหรือขอบล่าง

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


ดึงรายการลูก

**ค่าที่คืน:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


คุณสมบัติตัวอักษรควบคุม

**ค่าที่คืน:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps