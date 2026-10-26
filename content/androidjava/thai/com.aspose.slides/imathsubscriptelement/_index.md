---
title: IMathSubscriptElement
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: ระบุวัตถุตัวห้อยซึ่งประกอบด้วยฐานและตัวห้อยขนาดเล็กที่วางอยู่ด้านล่างและด้านขวา
type: docs
url: /th/com.aspose.slides/imathsubscriptelement/
---
**ทุกอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

ระบุวัตถุตัวห้อย ซึ่งประกอบด้วยฐานและตัวห้อยขนาดเล็กที่วางอยู่ด้านล่างและด้านขวา

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

**ผลลัพธ์:**
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

**ผลลัพธ์:**
[IMathElement](../../com.aspose.slides/imathelement)