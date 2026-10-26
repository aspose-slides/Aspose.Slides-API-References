---
title: group method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
يطّبق هذا العنصر في مجموعة باستخدام القوس المعقوف السفلي

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
يطّبق هذا العنصر في مجموعة باستخدام حرف تجميع مثل القوس المعقوف السفلي أو غيره

### Returns

New instance of type [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | حرف تجميع مثل BOTTOM CURLY BRACKET (U+23DF) أو أي حرف آخر |
| position | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | موضع حرف التجميع |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions) | محاذاة رأسية لحرف المجموعة.<br/><br/>            يحدد محاذاة الكائن بالنسبة إلى الخط الأساسي.<br/><br/>            على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، <br/><br/>            يشير VerticalJustification إلى Top إلى أن أعلى الكائن يقع على الخط الأساسي؛<br/><br/>            عندما يتم ضبط VerticalJustification إلى Bottom، يكون أسفل الكائن على الخط الأساسي |



### See Also
* فئة [`IMathGroupingCharacter`](/slides/python-net/ar/aspose.slides.mathtext/imathgroupingcharacter)
* فئة [`MathPhantom`](/slides/python-net/ar/aspose.slides.mathtext/mathphantom)
* تعداد [`MathTopBotPositions`](/slides/python-net/ar/aspose.slides.mathtext/mathtopbotpositions)
* وحدة [`aspose.slides.mathtext`](/slides/python-net/ar/aspose.slides.mathtext)
* مكتبة [`Aspose.Slides`](/slides/python-net)