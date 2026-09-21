---
title: group method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathbox/group/
weight: 80
---
## group(self) {#}
इस तत्व को एक समूह में रखता है नीचे कर्ली ब्रैकेट का उपयोग करके

### Returns
नया इंस्टेंस प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) के

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह में रखता है एक समूहिक वर्ण (जैसे नीचे कर्ली ब्रैकेट या कोई अन्य) का उपयोग करके

### Returns
नया इंस्टेंस प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) के

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | समूहिक वर्ण जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूहिक वर्ण की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह वर्ण की ऊर्ध्वाधर संरेखण।<br/><br/>ऑब्जेक्ट की बेसलाइन के सापेक्ष संरेखण निर्धारित करता है।<br/><br/>उदाहरण के लिए, जब समूह वर्ण ऑब्जेक्ट के ऊपर हो, <br/><br/>VerticalJustification of Top संकेत करता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर स्थित है;<br/><br/>जब VerticalJustification को Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला भाग बेसलाइन पर रहता है |

### See Also
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathBox`](/slides/python-net/hi/aspose.slides.mathtext/mathbox)
* एन्युमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)