---
title: group method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathsuperscriptelement/group/
weight: 80
---
## group(self) {#}
يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### الإرجاع

مثيل جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره

### الإرجاع

مثيل جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| character | **char** | حرف تجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | تحديد الاتجاه العمودي لحرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة للخط الأساسي.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، <br/><br/>            يشير VerticalJustification إلى الأعلى بأن الجزء العلوي من الكائن يقع على الخط الأساسي؛<br/><br/>            عندما يتم ضبط VerticalJustification على Bottom، يكون الجزء السفلي من الكائن على الخط الأساسي |



### راجع أيضًا
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* فئة [`MathSuperscriptElement`](/slides/python-net/ar/aspose.slides.mathtext/mathsuperscriptelement)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)