---
title: group method
second_title: Aspose.Slides फ़ॉर पायथन द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathematicaltext/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है

### Returns
नए प्रकार की instance [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह बनाने वाले कैरेक्टर जैसे नीचे की कर्ली ब्रैकेट या अन्य किसी कैरेक्टर का उपयोग करके समूह में रखता है

### Returns
नए प्रकार की instance [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | ग्रुपिंग कैरेक्टर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | ग्रुपिंग कैरेक्टर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | ग्रुप कैरेक्टर का वर्टिकल जस्टिफिकेशन।<br/><br/>ऑब्जेक्ट की बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है।<br/><br/>उदाहरण के लिए, जब ग्रुप कैरेक्टर ऑब्जेक्ट के ऊपर हो, <br/><br/>VerticalJustification of Top यह दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर स्थित है;<br/><br/>जब VerticalJustification को Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला भाग बेसलाइन पर होता है |

### See Also
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathematicalText`](/slides/python-net/hi/aspose.slides.mathtext/mathematicaltext)
* enumeration [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)