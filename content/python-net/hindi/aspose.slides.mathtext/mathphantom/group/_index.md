---
title: group method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
इस तत्व को एक समूह में रखता है नीचे की कर्ली ब्रैकेट का उपयोग करके

### परिणाम

New instance of type [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह में रखता है, जहाँ समूह बनाने वाला अक्षर नीचे की कर्ली ब्रैकेट या कोई अन्य हो सकता है

### परिणाम

New instance of type [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूह बनाने वाला अक्षर, जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह बनाने वाले अक्षर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | Group character की vertical justification.<br/><br/>            वस्तु के baseline के सापेक्ष संरेखण को निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब group character वस्तु के ऊपर हो, <br/><br/>            VerticalJustification of Top यह दर्शाता है कि वस्तु का शीर्ष baseline पर स्थित है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, वस्तु का निचला भाग baseline पर होता है |



### संबंधित देखें
* कक्षा [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* कक्षा [`MathPhantom`](/slides/python-net/hi/aspose.slides.mathtext/mathphantom)
* enumeration [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)