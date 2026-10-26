---
title: IMathBar
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ระบุฟังก์ชันบาร์ที่ประกอบด้วยอาร์กิวเมนต์ฐานและบาร์เหนือหรือบาร์ล่าง
type: docs
url: /th/com.aspose.slides/imathbar/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

ระบุฟังก์ชันบาร์ ที่ประกอบด้วยอาร์กิวเมนต์ฐานและบาร์เหนือหรือบาร์ล่าง

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getPosition()](#getPosition--) | ตำแหน่งของบรรทัดบาร์ |
| [setPosition(int value)](#setPosition-int-) | ตำแหน่งของบรรทัดบาร์ |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


ตำแหน่งของบรรทัดบาร์ ค่าเริ่มต้น: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**คืนค่า:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


ตำแหน่งของบรรทัดบาร์ ค่าเริ่มต้น: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |