---
title: IMathLimit
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: ระบุอ็อบเจกต์ Limit ซึ่งประกอบด้วยข้อความบนเส้นฐานและข้อความที่มีขนาดเล็กลงที่อยู่เหนือหรือใต้โดยตรง
type: docs
url: /th/com.aspose.slides/imathlimit/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

ระบุอ็อบเจกต์ Limit ซึ่งประกอบด้วยข้อความบนเส้นฐานและข้อความขนาดลดลงที่อยู่เหนือหรือใต้ตรงนั้นโดยตรง.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getLimit()](#getLimit--) | อาร์กิวเมนต์จำกัด |
| [getUpperLimit()](#getUpperLimit--) | ระบุขอบเขตบนหรือขอบเขตล่าง |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | ระบุขอบเขตบนหรือขอบเขตล่าง |
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

ระบุขอบเขตบนหรือขอบเขตล่าง

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

ระบุขอบเขตบนหรือขอบเขตล่าง

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