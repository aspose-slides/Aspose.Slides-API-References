---
title: IMathematicalText
second_title: Aspose.Slides สำหรับ Java API Reference
description: ข้อความคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathematicaltext/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

ข้อความคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getValue()](#getValue--) | ค่าข้อความ |
| [setValue(String value)](#setValue-java.lang.String-) | ค่าข้อความ |
| [getFormat()](#getFormat--) | คุณสมบัติการจัดรูปแบบข้อความ |
### getValue() {#getValue--}
```
public abstract String getValue()
```


ค่าข้อความ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**ค่าที่ส่งกลับ:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```


ค่าข้อความ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```


คุณสมบัติการจัดรูปแบบข้อความ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**ค่าที่ส่งกลับ:**
[IPortionFormat](../../com.aspose.slides/iportionformat)