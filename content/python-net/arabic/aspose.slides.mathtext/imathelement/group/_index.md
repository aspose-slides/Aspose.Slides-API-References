---
title: group method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/imathelement/group/
weight: 70
---
## group(self) {#}
يوضع هذا العنصر في مجموعة باستخدام قوس مجعد سفلي

### الإرجاع

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يوضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المجعد السفلي أو غيره

### الإرجاع

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| character | **char** | حرف التجميع مثل القوس المجعد السفلي (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة عمودية لحرف التجميع.<br/><br/>            يحدد محاذاة الكائن بالنسبة لخط القاعدة.<br/><br/>            على سبيل المثال، عندما يكون حرف التجميع فوق الكائن، <br/><br/>            تُشير VerticalJustification إلى الأعلى إلى أن الجزء العلوي من الكائن يقع على خط القاعدة؛<br/><br/>            عندما يتم تعيين VerticalJustification إلى الأسفل، يكون الجزء السفلي من الكائن على خط القاعدة |



### انظر أيضًا
* فئة [`IMathElement`](/slides/python-net/ar/aspose.slides.mathtext/imathelement)
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* التعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* الوحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* المكتبة [`Aspose.Slides`](/slides/python-net)