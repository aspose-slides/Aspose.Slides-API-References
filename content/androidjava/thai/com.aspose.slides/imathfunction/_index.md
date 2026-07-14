---
title: IMathFunction
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ระบุฟังก์ชันของอาร์กิวเมนต์
type: docs
url: /th/com.aspose.slides/imathfunction/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

ระบุตัวฟังก์ชันของอาร์กิวเมนต์

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getName()](#getName--) | ชื่อฟังก์ชัน ตัวอย่างเช่น ชื่อฟังก์ชันคือ sin และ cos |
| [getBase()](#getBase--) | อาร์กิวเมนต์ของฟังก์ชัน |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


ชื่อฟังก์ชัน ตัวอย่างเช่น ชื่อฟังก์ชันคือ sin และ cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


อาร์กิวเมนต์ของฟังก์ชัน

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)