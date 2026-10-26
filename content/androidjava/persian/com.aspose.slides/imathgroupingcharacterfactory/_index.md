---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: امکان ایجاد یک کاراکتر گروه‌بندی ریاضی
type: docs
url: /fa/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

اجازه می‌دهد کاراکتر گروه‌بندی ریاضی ایجاد شود

--------------------

برای سازگاری با COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال کاراکتر گروه‌بندی |
| character | char | کاراکتر گروه‌بندی |
| position | int | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | int | تراز عمودی |

**بازگشت:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر جدید کاراکتر گروه‌بندی

### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال کاراکتر گروه‌بندی |

**بازگشت:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر جدید کاراکتر گروه‌بندی