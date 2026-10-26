---
title: IMathematicalText
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: ข้อความคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathematicaltext/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Mathematical text

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getValue()](#getValue--) | ค่าแบบข้อความ |
| [setValue(String value)](#setValue-java.lang.String-) | ค่าแบบข้อความ |
| [getFormat()](#getFormat--) | คุณสมบัติการจัดรูปแบบข้อความ |
### getValue() {#getValue--}
```
public abstract String getValue()
```


ค่าแบบข้อความ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
>  ```


**คืนค่า:**  
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```


ค่าแบบข้อความ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
>  ```

**พารามิเตอร์:**
| Parameter | Type | คำอธิบาย |
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

**คืนค่า:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)