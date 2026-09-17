---
title: group method
second_title: Aspose.Slides للغة Python عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathlimit/group/
weight: 80
---
## group(self) {#}
يضع هذا العنصر في مجموعة باستخدام قوس معقوف سفلي

### الإرجاع
مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يضع هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره

### الإرجاع
مثال جديد من النوع [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| character | **char** | حرف تجميع مثل القوس المعقوف السفلي (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة عمودية لحرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة إلى خط الأساس.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة أعلى الكائن، <br/><br/>            محاذاة عمودية إلى الأعلى تشير إلى أن الجزء العلوي من الكائن يقع على خط الأساس؛<br/><br/>            عند ضبط محاذاة عمودية إلى الأسفل، يكون الجزء السفلي من الكائن على خط الأساس |



### أنظر أيضاً
* class [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathLimit`](/slides/python-net/ar/aspose.slides.mathtext/mathlimit)
* enumeration [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)