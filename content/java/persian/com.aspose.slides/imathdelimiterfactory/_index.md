---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: اجازه می‌دهد یک جداساز ریاضی ایجاد کند
type: docs
url: /fa/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

یک جداساز ریاضی ایجاد می‌کند

--------------------

برای مقایسه‌پذیری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

یک جداساز ریاضی را با اعمال به عنصر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply delimiter |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - new math delimiter
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

یک جداساز ریاضی را با اعمال به عنصر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math elements to apply delimiter |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - new math delimiter