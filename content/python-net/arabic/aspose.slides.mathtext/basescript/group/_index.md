---
title: group method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description:
type: docs
url: /ar/aspose.slides.mathtext/basescript/group/
weight: 70
---
## group(self) {#}
يضع هذا العنصر في مجموعة باستخدام قوس معكوف سفلي

### Returns

كائن جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعكوف السفلي أو غيره

### Returns

كائن جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | حرف تجميع مثل القوس المعكوف السفلي (U+23DF) أو أي آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة رأسية لحرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة لخط الأساس.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، <br/><br/>            تشير محاذاة رأسية إلى الأعلى إلى أن أعلى الكائن يقع على خط الأساس؛<br/><br/>            عندما يتم ضبط المحاذاة الرأسية إلى أسفل، يكون أسفل الكائن على خط الأساس |

### See Also
* فئة [`BaseScript`](/slides/python-net/ar/aspose.slides.mathtext/basescript)
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)