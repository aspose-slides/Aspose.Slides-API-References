---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: امکان ایجاد یک لهجهٔ ریاضی را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

امکان ایجاد یک لهجهٔ ریاضی را فراهم می‌کند

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | یک لهجهٔ ریاضی را برای عنصر ریاضی مشخص شده، با مقدار پیش‌فرض کاراکتر لهجه، ایجاد می‌کند |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | یک لهجهٔ ریاضی را برای عنصر ریاضی مشخص شده ایجاد می‌کند |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

یک لهجهٔ ریاضی را برای عنصر ریاضی مشخص شده، با مقدار پیش‌فرض کاراکتر لهجه، ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال لهجه |
**باز می‌گرداند:**
[IMathAccent](../../com.aspose.slides/imathaccent) - یک لهجهٔ ریاضی جدید
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

یک لهجهٔ ریاضی را برای عنصر ریاضی مشخص شده ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال لهجه |
| accentCharacter | char | کاراکتر لهجه |
**باز می‌گرداند:**
[IMathAccent](../../com.aspose.slides/imathaccent) - یک لهجهٔ ریاضی جدید