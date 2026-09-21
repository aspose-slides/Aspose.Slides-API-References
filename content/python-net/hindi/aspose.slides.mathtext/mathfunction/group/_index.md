---
title: group method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathfunction/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके समूह में रखता है

### Returns
New instance of type [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह में रखने के लिए एक समूहित वर्ण का उपयोग करता है, जैसे नीचे की कर्ली ब्रैकेट या कोई अन्य

### Returns
New instance of type [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूहित वर्ण, जैसे नीचे की कर्ली ब्रैकेट (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूहित वर्ण की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह वर्ण का ऊर्ध्वाधर संरेखण।<br/><br/>            वस्तु के बेसलाइन के सापेक्ष संरेखण को निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब समूह वर्ण वस्तु के ऊपर होता है, <br/><br/>            Top का VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर आता है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, तब वस्तु का नीचे बेसलाइन पर होता है |

### See Also
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathFunction`](/slides/python-net/hi/aspose.slides.mathtext/mathfunction)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)