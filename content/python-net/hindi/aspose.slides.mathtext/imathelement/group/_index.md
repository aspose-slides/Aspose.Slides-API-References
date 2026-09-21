---
title: group method
second_title: Aspose.Slides पाइथन के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/imathelement/group/
weight: 70
---
## group(self) {#}
इस तत्व को नीचे के कर्ली ब्रैकेट का उपयोग करके समूह में रखता है

### Returns
वापसी

नई प्रकार की इंस्टेंस [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह अक्षर का उपयोग करके समूह में रखता है, जैसे नीचे का कर्ली ब्रैकेट या कोई अन्य

### Returns
वापसी

नई प्रकार की इंस्टेंस [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूह अक्षर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह अक्षर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह अक्षर की ऊर्ध्वाधर उचितता।<br/><br/>            ऑब्जेक्ट का बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब समूह अक्षर ऑब्जेक्ट के ऊपर हो, <br/><br/>            Top की VerticalJustification दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर है;<br/><br/>            जब VerticalJustification Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला भाग बेसलाइन पर रहता है |

### See Also
* वर्ग [`IMathElement`](/slides/python-net/hi/aspose.slides.mathtext/imathelement)
* वर्ग [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* enumeration [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)