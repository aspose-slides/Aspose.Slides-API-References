---
title: group method
second_title: مرجع واجهة برمجة التطبيقات لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### القيمة المرجعة

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو أي حرف آخر

### القيمة المرجعة

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | حرف التجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة عمودية لحرف المجموعة.<br/><br/>            يحدد موضع الكائن بالنسبة إلى خط الأساس.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة أعلى الكائن، <br/><br/>            تشير محاذاة عمودية إلى الأعلى إلى أن أعلى الكائن يقع على خط الأساس؛<br/><br/>            عندما يتم تعيين محاذاة عمودية إلى الأسفل، يكون أسفل الكائن على خط الأساس |

### انظر أيضًا
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* فئة [`MathAccent`](/slides/python-net/ar/aspose.slides.mathtext/mathaccent)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)