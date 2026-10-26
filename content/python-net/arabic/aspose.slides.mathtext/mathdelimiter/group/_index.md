---
title: group method
second_title: مرجعية API ل Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
يضع هذا العنصر في مجموعة باستخدام قوس تجعيد سفلي

### القيمة المرجعة

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل قوس تجعيد سفلي أو أي حرف آخر

### القيمة المرجعة

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| character | **char** | حرف تجميع مثل قوس تجعيد سفلي (BOTTOM CURLY BRACKET) (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة رأسية لحرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة إلى الخط الأساسي.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، <br/><br/>            تشير المحاذاة الرأسية `Top` إلى أن أعلى الكائن يقع على الخط الأساسي;<br/><br/>            عندما تُضبط المحاذاة الرأسية على `Bottom`، يكون أسفل الكائن على الخط الأساسي |



### انظر أيضًا
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* فئة [`MathDelimiter`](/slides/python-net/ar/aspose.slides.mathtext/mathdelimiter)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)