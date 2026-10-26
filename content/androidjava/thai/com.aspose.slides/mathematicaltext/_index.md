---
title: MathematicalText
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: ข้อความคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathematicaltext/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

ข้อความคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | คอนสตรัคเตอร์เริ่มต้น (สร้างค่า String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | สร้าง MathText ด้วยสัญลักษณ์เดียว |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | สร้าง MathematicalText จากข้อความ |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | สร้าง MathematicalText จากข้อความและการตั้งค่ารูปแบบ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getValue()](#getValue--) | ค่าข้อความ |
| [setValue(String value)](#setValue-java.lang.String-) | ค่าข้อความ |
| [getFormat()](#getFormat--) | คุณสมบัติการจัดรูปแบบข้อความ |
| [getChildren()](#getChildren--) | รับสมาชิกลูก |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```

คอนสตรัคเตอร์เริ่มต้น (สร้างค่า String.Empty)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```

สร้าง MathText ด้วยสัญลักษณ์เดียว

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathSymbol | char | สัญลักษณ์เดียว |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```

สร้าง MathematicalText จากข้อความ

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```

สร้าง MathematicalText จากข้อความและการตั้งค่ารูปแบบ

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | การตั้งค่ารูปแบบข้อความ |

### getValue() {#getValue--}
```
public final String getValue()
```

ค่าข้อความ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**ผลลัพธ์:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```

คุณสมบัติการจัดรูปแบบข้อความ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**ผลลัพธ์:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับสมาชิกลูก

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]