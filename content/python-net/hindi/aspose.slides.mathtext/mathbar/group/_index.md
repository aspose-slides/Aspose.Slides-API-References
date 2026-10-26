---
title: group method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathbar/group/
weight: 80
---
## group(self) {#}
इस तत्व को एक समूह में रखता है, जिसमें नीचे का कर्ली ब्रैकेट उपयोग किया जाता है

### रिटर्न

प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) का नया उदाहरण



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को एक समूह में रखता है, जिसमें नीचे का कर्ली ब्रैकेट या अन्य जैसे समूहिंग कैरेक्टर का उपयोग किया जाता है

### रिटर्न

प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) का नया उदाहरण



```python
def group(self, character, position, vertical_justification):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूहिंग कैरेक्टर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूहिंग कैरेक्टर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह कैरेक्टर का वर्टिकल सज्जा।<br/><br/>            वस्तु की बेसलाइन के संबंध में संरेखण को निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब समूह कैरेक्टर वस्तु के ऊपर होता है, <br/><br/>            VerticalJustification of Top संकेत करता है कि वस्तु का शीर्ष बेसलाइन पर स्थित है;<br/><br/>            जब VerticalJustification को Bottom पर सेट किया जाता है, वस्तु का निचला हिस्सा बेसलाइन पर रहता है |



### देखें
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathBar`](/slides/python-net/hi/aspose.slides.mathtext/mathbar)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)