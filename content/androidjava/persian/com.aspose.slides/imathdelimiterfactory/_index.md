---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math delimiter
type: docs
url: /fa/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

اجازه می‌دهد یک جداکننده ریاضی ایجاد شود

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | یک جداکننده ریاضی را با اعمال بر عنصر ایجاد می‌کند |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | یک جداکننده ریاضی را با اعمال بر عنصر ایجاد می‌کند |
### createMathDelimiter(IMMathElement element) {#createMathDelimiter-com.aspose.slides.IMMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

یک جداکننده ریاضی را با اعمال بر عنصر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال جداکننده |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - جدید جداکننده ریاضی
### createMathDelimiter(IMMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

یک جداکننده ریاضی را با اعمال بر عنصر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | عناصر ریاضی برای اعمال جداکننده |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - جدید جداکننده ریاضی