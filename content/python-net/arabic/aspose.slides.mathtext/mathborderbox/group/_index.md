---
title: group method
second_title: مرجع API لـ Aspose.Slides لبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathborderbox/group/
weight: 80
---
## group(self) {#}
يقوم بوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### القيمة المرجعة

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يقوم بوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو أي حرف آخر

### القيمة المرجعة

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| معامل | نوع | وصف |
| :- | :- | :- |
| character | **char** | حرف تجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة رأسية لحرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة إلى خط الأساس.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، <br/><br/>            تشير المحاذاة الرأسية Top إلى أن الجزء العلوي من الكائن يقع على خط الأساس؛<br/><br/>            عندما يتم تعيين المحاذاة الرأسية إلى Bottom، يكون الجزء السفلي من الكائن على خط الأساس |

### انظر أيضا
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* فئة [`MathBorderBox`](/slides/python-net/ar/aspose.slides.mathtext/mathborderbox)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)