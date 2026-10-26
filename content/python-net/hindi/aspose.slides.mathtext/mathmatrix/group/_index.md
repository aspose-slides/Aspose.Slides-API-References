---
title: group method
second_title: Aspose.Slides Python के लिए via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके समूह में रखता है

### Returns
नया उदाहरण प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूहिंग अक्षर जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करके समूह में रखता है

### Returns
नया उदाहरण प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | समूहिंग वर्ण जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूहिंग वर्ण की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | ग्रुप वर्ण की वर्टिकल जस्टिफिकेशन।<br/><br/>            वस्तु के बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब ग्रुप वर्ण वस्तु के ऊपर हो,<br/><br/>            VerticalJustification of Top दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर आता है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला हिस्सा बेसलाइन पर रहता है |

### See Also
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathMatrix`](/slides/python-net/hi/aspose.slides.mathtext/mathmatrix)
* एनेमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)