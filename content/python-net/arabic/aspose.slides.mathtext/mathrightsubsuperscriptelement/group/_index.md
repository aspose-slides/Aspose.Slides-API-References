---
title: group method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### الإرجاع
كائن جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره

### الإرجاع
كائن جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| character | **char** | حرف تجميع مثل BOTTOM CURLY BRACKET (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة رأسية لحرف التجميع.<br/><br/>            يحدد موضع الكائن بالنسبة لخط الأساس.<br/><br/>            على سبيل المثال، عندما يكون حرف التجميع فوق الكائن، <br/><br/>            يعني VerticalJustification من Top أن أعلى الكائن يقع على خط الأساس;<br/><br/>            عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط الأساس |

### انظر أيضًا
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* فئة [`MathRightSubSuperscriptElement`](/slides/python-net/ar/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)