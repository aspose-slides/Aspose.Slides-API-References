---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يسمح بإنشاء حرف تجميع رياضي
type: docs
url: /ar/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

يسمح بإنشاء حرف تجميع رياضي

--------------------

للتوافق مع COM
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق حرف التجميع |
| character | char | حرف التجميع |
| position | int | موضع حرف التجميع |
| verticalJustification | int | محاذاة رأسية |

**القيمة المرجعة:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر حرف تجميع جديد
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


ينشئ حرف تجميع رياضي

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق حرف التجميع |

**القيمة المرجعة:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر حرف تجميع جديد