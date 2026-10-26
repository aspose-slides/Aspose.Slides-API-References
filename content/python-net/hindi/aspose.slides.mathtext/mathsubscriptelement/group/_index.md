---
title: group method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathsubscriptelement/group/
weight: 80
---
## group(self) {#}
इस तत्व को निचले कर्ली ब्रैकेट का उपयोग करके समूह में रखता है

### Returns

नया उदाहरण प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
एक समूहिंग वर्ण जैसे निचला कर्ली ब्रैकेट या कोई अन्य का उपयोग करके इस तत्व को समूह में रखता है

### Returns

नया उदाहरण प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूहिंग वर्ण जैसे निचला कर्ली ब्रैकेट (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूहिंग वर्ण की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह वर्ण का लंबवत संरेखण।<br/><br/>            ऑब्जेक्ट को बेसलाइन के सापेक्ष संरेखित करने का निर्धारण करता है।<br/><br/>            उदाहरण के लिए, जब समूह वर्ण ऑब्जेक्ट के ऊपर हो, <br/><br/>            VerticalJustification of Top दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर आता है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला भाग बेसलाइन पर रहता है |



### देखें भी
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathSubscriptElement`](/slides/python-net/hi/aspose.slides.mathtext/mathsubscriptelement)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)