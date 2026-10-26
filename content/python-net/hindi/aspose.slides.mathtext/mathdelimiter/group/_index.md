---
title: group method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है

### रिटर्न
New instance of type [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को एक समूह में रखने के लिए समूह बनाने वाले अक्षर जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करता है

### रिटर्न
New instance of type [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूह बनाने वाला अक्षर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह बनाने वाले अक्षर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह अक्षर का ऊर्ध्वाधर संरेखण।<br/><br/>            वस्तु की बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर हो, <br/><br/>            VerticalJustification of Top दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर आता है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है |

### संबंधित देखें
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathDelimiter`](/slides/python-net/hi/aspose.slides.mathtext/mathdelimiter)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)