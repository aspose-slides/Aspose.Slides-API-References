---
title: MathematicalText
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: متن ریاضی
type: docs
url: /fa/com.aspose.slides/mathematicaltext/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

متن ریاضی

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | سازنده پیش‌فرض (ایجاد مقدار String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | ایجاد MathText با یک نماد واحد |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | ایجاد MathematicalText از متن |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | ایجاد MathematicalText از متن و تنظیمات قالب |
## متدها

| متد | توضیح |
| --- | --- |
| [getValue()](#getValue--) | مقدار متن |
| [setValue(String value)](#setValue-java.lang.String-) | مقدار متن |
| [getFormat()](#getFormat--) | ویژگی‌های قالب‌بندی متن |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```

سازنده پیش‌فرض (ایجاد مقدار String.Empty)

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

ایجاد MathText با یک نماد واحد

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathSymbol | char | یک نماد واحد |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```

ایجاد MathematicalText از متن

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```

ایجاد MathematicalText از متن و تنظیمات قالب

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | تنظیمات قالب متن |

### getValue() {#getValue--}
```
public final String getValue()
```

مقدار متن

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**بازگشت:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```

مقدار متن

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```

ویژگی‌های قالب‌بندی متن

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**بازگشت:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]