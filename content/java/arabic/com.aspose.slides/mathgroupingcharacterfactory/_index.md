---
title: MathGroupingCharacterFactory
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يسمح بإنشاء حرف تجميع رياضي
type: docs
url: /ar/com.aspose.slides/mathgroupingcharacterfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

يسمح بإنشاء حرف تجميع رياضي

--------------------

لتوافق COM
## المنشئين

| المنشئ | الوصف |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## الدوال

| الطريقة | الوصف |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | ينشئ حرف تجميع رياضي |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | ينشئ حرف تجميع رياضي |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


ينشئ حرف تجميع رياضي

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق حرف التجميع |
| character | char | حرف التجميع |
| position | int | موضع حرف التجميع |
| verticalJustification | int | المحاذاة العمودية |

**القيمة المرجعة:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر حرف تجميع جديد
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


ينشئ حرف تجميع رياضي

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق حرف التجميع |

**القيمة المرجعة:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - عنصر حرف تجميع جديد