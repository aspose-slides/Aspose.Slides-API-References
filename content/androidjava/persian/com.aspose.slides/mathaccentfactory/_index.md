---
title: MathAccentFactory
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: امکان ایجاد یک لهجه ریاضی را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/mathaccentfactory/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)  
```
public class MathAccentFactory implements IMathAccentFactory
```

اجازه ایجاد یک لهجه ریاضی

--------------------

برای سازگاری با COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | یک لهجه ریاضی ایجاد می‌کند که بر یک عنصر ریاضی مشخص با مقدار پیش‌فرض کاراکتر لهجه اعمال می‌شود |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | یک لهجه ریاضی ایجاد می‌کند که بر یک عنصر ریاضی مشخص اعمال می‌شود |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

یک لهجه ریاضی ایجاد می‌کند که بر یک عنصر ریاضی مشخص با مقدار پیش‌فرض کاراکتر لهجه اعمال می‌شود

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال لهجه |
**بازگشت:**
[IMathAccent](../../com.aspose.slides/imathaccent) - لهجهٔ ریاضی جدید
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

یک لهجه ریاضی ایجاد می‌کند که بر یک عنصر ریاضی مشخص اعمال می‌شود

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال لهجه |
| accentCharacter | char | کاراکتر لهجه |
**بازگشت:**
[IMathAccent](../../com.aspose.slides/imathaccent) - لهجهٔ ریاضی جدید