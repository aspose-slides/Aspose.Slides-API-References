---
title: group method
second_title: Aspose.Slides के लिए Python द्वारा .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathaccent/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके समूह में रखता है

### Returns
प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) का नया इंस्टेंस



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को किसी समूह बनाने वाले अक्षर जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करके समूह में रखता है

### Returns
प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) का नया इंस्टेंस



```python
def group(self, character, position, vertical_justification):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूह बनाने वाला अक्षर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह बनाने वाले अक्षर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | ग्रुप अक्षर की लंबवत न्यायसंगतता।<br/><br/>            बेसलाइन के सापेक्ष ऑब्जेक्ट के संरेखण को निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब ग्रुप अक्षर ऑब्जेक्ट के ऊपर हो, <br/><br/>            Top की VerticalJustification का अर्थ है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर स्थित है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला हिस्सा बेसलाइन पर होता है |



### See Also
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathAccent`](/slides/python-net/hi/aspose.slides.mathtext/mathaccent)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)