---
title: group method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathelementbase/group/
weight: 70
---
## group(self) {#}
يوضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### الإرجاع

نسخة جديدة من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو أي حرف آخر

### الإرجاع

نسخة جديدة من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| character | **char** | حرف تجميع مثل BOTTOM CURLY BRACKET (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة عمودية لحرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة إلى الخط الأساسي.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، <br/><br/>            VerticalJustification من Top يشير إلى أن أعلى الكائن يقع على الخط الأساسي؛<br/><br/>            عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على الخط الأساسي |



### انظر أيضًا
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* فئة [`MathElementBase`](/slides/python-net/ar/aspose.slides.mathtext/mathelementbase)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)