---
title: IMathematicalTextFactory
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: امکان ایجاد یک عنصر MathematicalText را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

امکان ایجاد یک عنصر MathematicalText را فراهم می‌کند

--------------------

برای قابلیت مقایسه‌ای COM
## روش‌ها

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | ایجاد یک عنصر متن ریاضی خالی |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | ایجاد عنصر متن ریاضی با مقدار مشخص شده |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | ایجاد یک عنصر متن ریاضی خالی با مقدار مشخص شده |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | ایجاد یک عنصر متن ریاضی خالی با مقدار مشخص شده و ویژگی‌های قالب‌بندی |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


ایجاد یک عنصر متن ریاضی خالی

**باز می‌گرداند:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جدید Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


ایجاد عنصر متن ریاضی با مقدار مشخص شده

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathSymbol | char | یک نماد واحد برای استفاده به عنوان مقدار متن |

**باز می‌گرداند:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جدید Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


ایجاد یک عنصر متن ریاضی خالی با مقدار مشخص شده

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |

**باز می‌گرداند:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جدید Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


ایجاد یک عنصر متن ریاضی خالی با مقدار مشخص شده و ویژگی‌های قالب‌بندی

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | تنظیمات قالب متن |

**باز می‌گرداند:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جدید Mathematical Text