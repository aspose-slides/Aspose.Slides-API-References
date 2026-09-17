---
title: group method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathgroupingcharacter/group/
weight: 80
---
## group(self) {#}
يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### إرجاع
مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره

### إرجاع
مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| character | **char** | حرف التجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | عمودية محاذاة حرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة لخط الأساس.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، <br/><br/>            VerticalJustification of Top تعني أن أعلى الكائن يقع على خط الأساس;<br/><br/>            عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط الأساس |

### انظر أيضًا
* الفئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* الفئة [`MathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/mathgroupingcharacter)
* التعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)