---
title: group method
second_title: Aspose.Slides for Python द्वारा .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathsuperscriptelement/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है

### रिटर्न

टाइप [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) की नई इंस्टेंस



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह में रखने के लिये एक ग्रुपिंग कैरेक्टर का उपयोग करता है जैसे नीचे की कर्ली ब्रैकेट या अन्य

### रिटर्न

टाइप [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) की नई इंस्टेंस



```python
def group(self, character, position, vertical_justification):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | ग्रुपिंग कैरेक्टर जैसे नीचे की कर्ली ब्रैकेट (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | ग्रुपिंग कैरेक्टर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | ग्रुप कैरेक्टर का वर्टिकल जस्टिफिकेशन।<br/><br/>            ऑब्जेक्ट की बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिये, जब ग्रुप कैरेक्टर ऑब्जेक्ट के ऊपर होता है, <br/><br/>            Top का VerticalJustification यह दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर आता है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला हिस्सा बेसलाइन पर होता है |



### देखें
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathSuperscriptElement`](/slides/python-net/hi/aspose.slides.mathtext/mathsuperscriptelement)
* एन्युमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)