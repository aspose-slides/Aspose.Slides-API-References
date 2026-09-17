---
title: group method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathsubscriptelement/group/
weight: 80
---
## group(self) {#}
يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### Returns
مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل قوس معقوف سفلي أو غيره

### Returns
مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | حرف التجميع مثل BOTTOM CURLY BRACKET (U+23DF) أو أي آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة عمودية لحرف التجميع.<br/><br/> يحدد موضع الكائن بالنسبة للخط الأساسي.<br/><br/> على سبيل المثال، عندما يكون حرف التجميع فوق الكائن، <br/><br/> VerticalJustification of Top يعني أن أعلى الكائن يقع على الخط الأساسي;<br/><br/> عندما يكون VerticalJustification مضبوطًا على Bottom، يكون أسفل الكائن على الخط الأساسي |

### See Also
* الفئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* الفئة [`MathSubscriptElement`](/slides/python-net/ar/aspose.slides.mathtext/mathsubscriptelement)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)