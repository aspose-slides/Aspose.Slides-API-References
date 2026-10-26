---
title: group method
second_title: Aspose.Slides لبايثون عبر مرجع API .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathleftsubsuperscriptelement/group/
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
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل قوس معقوف سفلي أو غيره

### القيمة المرجعة
مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | حرف التجميع مثل BOTTOM CURLY BRACKET (U+23DF) أو أي آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة رأسية لحرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة إلى خط القاعدة.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، <br/><br/>            تشير VerticalJustification إلى الأعلى إلى أن الجزء العلوي من الكائن يقع على خط القاعدة؛<br/><br/>            عندما يتم تعيين VerticalJustification إلى Bottom، يكون الجزء الأسفل من الكائن على خط القاعدة |

### انظر أيضًا
* الفئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* الفئة [`MathLeftSubSuperscriptElement`](/slides/python-net/ar/aspose.slides.mathtext/mathleftsubsuperscriptelement)
* التعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)