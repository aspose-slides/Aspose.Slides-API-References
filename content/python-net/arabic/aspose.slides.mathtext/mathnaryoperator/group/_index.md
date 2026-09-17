---
title: group method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathnaryoperator/group/
weight: 80
---
## group(self) {#}
يوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### الإرجاع

مثيل جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو أي حرف آخر

### الإرجاع

مثيل جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | حرف التجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة عمودية لحرف التجميع.<br/><br/>            يحدد محاذاة الكائن بالنسبة إلى خط الأساس.<br/><br/>            على سبيل المثال، عندما يكون حرف التجميع فوق الكائن, <br/><br/>            VerticalJustification of Top signifies that the top of the object falls on the baseline;<br/><br/>            عندما يتم تعيين VerticalJustification إلى Bottom، يكون الجزء السفلي من الكائن على خط الأساس |

### انظر أيضًا
* الفئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* الفئة [`MathNaryOperator`](/slides/python-net/ar/aspose.slides.mathtext/mathnaryoperator)
* التعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)