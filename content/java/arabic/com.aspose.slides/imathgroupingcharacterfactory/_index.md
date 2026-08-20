---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math grouping character
type: docs
url: /ar/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

يسمح بإنشاء حرف تجميع رياضي

--------------------

لتوافق COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | ينشئ حرف تجميع رياضي |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | ينشئ حرف تجميع رياضي |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

ينشئ حرف تجميع رياضي

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق حرف التجميع |
| character | char | حرف التجميع |
| position | int | موقع حرف التجميع |
| verticalJustification | int | محاذاة عمودية |

**الإرجاع:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر حرف تجميع جديد
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

ينشئ حرف تجميع رياضي

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق حرف التجميع |

**الإرجاع:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر حرف تجميع جديد