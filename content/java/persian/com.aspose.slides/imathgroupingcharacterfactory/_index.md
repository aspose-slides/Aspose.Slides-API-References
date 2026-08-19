---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math grouping character
type: docs
url: /fa/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند

--------------------

برای سازگاری COM
## متدها

| Method | Description |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال کاراکتر گروه‌بندی |
| character | char | کاراکتر گروه‌بندی |
| position | int | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | int | تراز عمودی |

**بازگشت:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر کاراکتر گروه‌بندی جدید
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


یک کاراکتر گروه‌بندی ریاضی ایجاد می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال کاراکتر گروه‌بندی |

**بازگشت:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر کاراکتر گروه‌بندی جدید