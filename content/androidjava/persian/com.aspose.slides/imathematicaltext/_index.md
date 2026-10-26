---
title: IMathematicalText
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: متن ریاضی
type: docs
url: /fa/com.aspose.slides/imathematicaltext/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

متن ریاضی

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getValue()](#getValue--) | مقدار متن |
| [setValue(String value)](#setValue-java.lang.String-) | مقدار متن |
| [getFormat()](#getFormat--) | خصوصیات قالب‌بندی متن |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
```

خصوصیات قالب‌بندی متن

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**بازگشت:**
[IPortionFormat](../../com.aspose.slides/iportionformat)