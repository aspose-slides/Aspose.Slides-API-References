---
title: MathematicalTextFactory
second_title: Aspose.Slides برای مرجع API جاوا
description: امکان ایجاد یک عنصر MathematicalText را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/mathematicaltextfactory/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)  
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

به شما امکان می‌دهد عنصر MathematicalText را ایجاد کنید

--------------------

برای سازگاری با COM  
## سازندها

| سازنده | توضیح |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

یک عنصر متن ریاضی خالی ایجاد می‌کند

**بازگرداندن:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - متن ریاضی جدید
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

عنصر متن ریاضی را با مقدار مشخص ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathSymbol | char | نماد منفردی که به‌عنوان مقدار متن استفاده می‌شود |

**بازگرداندن:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - متن ریاضی جدید
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

یک عنصر متن ریاضی خالی را با مقدار مشخص ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |

**بازگرداندن:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - متن ریاضی جدید
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

یک عنصر متن ریاضی خالی را با مقدار مشخص و ویژگی‌های قالب‌بندی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | تنظیمات قالب متن |

**بازگرداندن:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - متن ریاضی جدید