---
title: IMathematicalTextFactory
second_title: Aspose.Slides برای Java API Reference
description: اجازه می‌دهد یک عنصر MathematicalText ایجاد کند
type: docs
url: /fa/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

اجازه می‌دهد یک عنصر MathematicalText ایجاد کند

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | ایجاد عنصر MathematicalText خالی |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | ایجاد عنصر MathematicalText با مقدار مشخص شده |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | ایجاد عنصر MathematicalText خالی با مقدار مشخص شده |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | ایجاد عنصر MathematicalText خالی با مقدار مشخص شده و ویژگی‌های قالب‌بندی |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

ایجاد عنصر MathematicalText خالی

**بازمی‌گرداند:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جدید Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

ایجاد عنصر MathematicalText با مقدار مشخص شده

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathSymbol | char | نماد تک برای استفاده به عنوان مقدار متن |

**بازمی‌گرداند:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جدید Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

ایجاد عنصر MathematicalText خالی با مقدار مشخص شده

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |

**بازمی‌گرداند:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جدید Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

ایجاد عنصر MathematicalText خالی با مقدار مشخص شده و ویژگی‌های قالب‌بندی

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | مقدار متن |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | تنظیمات قالب متن |

**بازمی‌گرداند:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جدید Mathematical Text