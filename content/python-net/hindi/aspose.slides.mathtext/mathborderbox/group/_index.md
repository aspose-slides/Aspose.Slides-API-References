---
title: group method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathborderbox/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है

### रिटर्न

प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) का नया उदाहरण



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह बनाने वाले अक्षर जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करके एक समूह में रखता है

### रिटर्न

प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) का नया उदाहरण



```python
def group(self, character, position, vertical_justification):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूह बनाने वाला अक्षर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह बनाने वाले अक्षर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह अक्षर की लंबवत संरेखण।<br/><br/>            ऑब्जेक्ट की बेसलाइन के सापेक्ष संरेखण को निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब समूह अक्षर ऑब्जेक्ट के ऊपर हो, <br/><br/>            VerticalJustification of Top यह दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर स्थित है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला भाग बेसलाइन पर होता है |



### संबंधित देखें
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathBorderBox`](/slides/python-net/hi/aspose.slides.mathtext/mathborderbox)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)