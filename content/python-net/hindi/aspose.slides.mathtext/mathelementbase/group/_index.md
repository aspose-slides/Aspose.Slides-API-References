---
title: group method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathelementbase/group/
weight: 70
---
## group(self) {#}
इस तत्व को एक समूह में रखता है नीचे की कर्ली ब्रैकेट का उपयोग करके

### रिटर्न
प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) की नई इंस्टेंस



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को एक समूह में रखता है एक समूहित अक्षर जैसे नीचे की कर्ली ब्रैकेट या अन्य

### रिटर्न
प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) की नई इंस्टेंस



```python
def group(self, character, position, vertical_justification):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूहित अक्षर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूहित अक्षर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह अक्षर की लंबवत न्यायसंगतता।<br/><br/>            वस्तु की बेसलाइन के संबंध में संरेखण निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर होता है, <br/><br/>            Top का VerticalJustification संकेत करता है कि वस्तु का शीर्ष बेसलाइन पर आता है;<br/><br/>            जब HorizontalJustification Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर होता है |



### संबंधित देखें
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathElementBase`](/slides/python-net/hi/aspose.slides.mathtext/mathelementbase)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)