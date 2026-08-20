---
title: IMathSubscriptElement
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุวัตถุตัวห้อยซึ่งประกอบด้วยฐานและตัวห้อยขนาดย่อมที่วางอยู่ด้านล่างและด้านขวา.
type: docs
url: /th/com.aspose.slides/imathsubscriptelement/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

ระบุวัตถุตัวห้อยซึ่งประกอบด้วยฐานและตัวห้อยขนาดย่อมที่วางอยู่ด้านล่างและด้านขวา.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getSubscript()](#getSubscript--) | ตัวห้อย |
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
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
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
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)