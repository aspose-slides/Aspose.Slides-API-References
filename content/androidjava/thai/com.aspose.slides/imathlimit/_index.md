---
title: IMathLimit
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุอ็อบเจ็กต์ Limit ซึ่งประกอบด้วยข้อความบนเส้นฐานและข้อความขนาดย่อที่อยู่เหนือหรือใต้โดยทันที
type: docs
url: /th/com.aspose.slides/imathlimit/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

ระบุอ็อบเจ็กต์ Limit ซึ่งประกอบด้วยข้อความบนเส้นฐานและข้อความขนาดย่อที่อยู่เหนือหรือใต้โดยทันที

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getLimit()](#getLimit--) | อาร์กิวเมนต์จำกัด |
| [getUpperLimit()](#getUpperLimit--) | ระบุขอบบนหรือขอบล่าง |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | ระบุขอบบนหรือขอบล่าง |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```


อาร์กิวเมนต์จำกัด

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```


ระบุขอบบนหรือขอบล่าง

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**คืนค่า:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```


ระบุขอบบนหรือขอบล่าง

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |