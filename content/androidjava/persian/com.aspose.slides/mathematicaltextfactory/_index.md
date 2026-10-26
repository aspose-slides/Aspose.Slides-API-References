---
title: MathematicalTextFactory
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: اجازه می‌دهد یک عنصر MathematicalText ایجاد شود
type: docs
url: /fa/com.aspose.slides/mathematicaltextfactory/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

اجازه می‌دهد عنصر MathematicalText ایجاد شود

--------------------

برای سازگاری با COM
## سازنده‌ها

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


ایجاد عنصر متنی ریاضی خالی

**بازگشت:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


ایجاد عنصر متنی ریاضی با مقدار مشخص شده

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathSymbol | char | نماد تک برای استفاده به عنوان مقدار متن |

**بازگشت:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


ایجاد عنصر متنی ریاضی خالی با مقدار مشخص شده

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |

**بازگشت:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


ایجاد عنصر متنی ریاضی خالی با مقدار مشخص شده و ویژگی‌های قالب‌بندی

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | تنظیمات قالب متن |

**بازگشت:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text