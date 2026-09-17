---
title: group method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathblock/group/
weight: 130
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
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو أي حرف آخر

### القيمة المرجعة

مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| character | **char** | حرف التجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | المحاذاة العمودية لحرف التجميع.<br/><br/>            يحدد محاذاة الكائن بالنسبة لخط القاعدة.<br/><br/>            على سبيل المثال، عندما يكون حرف التجميع فوق الكائن، <br/><br/>            يعني VerticalJustification للقمة أن الجزء العلوي من الكائن يقع على خط القاعدة؛<br/><br/>            عندما يتم تعيين VerticalJustification إلى Bottom، يكون الجزء السفلي من الكائن على خط القاعدة |



### انظر أيضًا
* الفئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* الفئة [`MathBlock`](/slides/python-net/ar/aspose.slides.mathtext/mathblock)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)