---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math accent
type: docs
url: /fa/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

اجازه می‌دهد تا یک آکسنت ریاضی ایجاد شود

--------------------

برای قابلیت مقایسه COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | یک آکسنت ریاضی را برای یک عنصر ریاضی مشخص با مقدار پیش‌فرض کاراکتر آکسنت ایجاد می‌کند |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | یک آکسنت ریاضی را برای یک عنصر ریاضی مشخص ایجاد می‌کند |
### createMathAccent(IMMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMMathElement element)
```

یک آکسنت ریاضی را برای یک عنصر ریاضی مشخص با مقدار پیش‌فرض کاراکتر آکسنت ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال اکسنت |

**برگشت:**
[IMathAccent](../../com.aspose.slides/imathaccent) - آکسنت ریاضی جدید
### createMathAccent(IMMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMMathElement element, char accentCharacter)
```

یک آکسنت ریاضی را برای یک عنصر ریاضی مشخص ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال اکسنت |
| accentCharacter | char | کاراکتر اکسنت |

**برگشت:**
[IMathAccent](../../com.aspose.slides/imathaccent) - آکسنت ریاضی جدید