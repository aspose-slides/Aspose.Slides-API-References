---
title: group method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathfraction/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है

### रिटर्न
नया उदाहरण प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह बनाने वाले वर्ण का उपयोग करके एक समूह में रखता है, जैसे नीचे की कर्ली ब्रैकेट या कोई अन्य

### रिटर्न
नया उदाहरण प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूह बनाता वर्ण जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह बनाता वर्ण की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह वर्ण का वर्टिकल जस्टिफिकेशन.<br/><br/> ऑब्जेक्ट का बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है।<br/><br/> उदाहरण के लिए, जब समूह वर्ण ऑब्जेक्ट के ऊपर होता है, <br/><br/> VerticalJustification of Top संकेत करता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर आता है;<br/><br/> जब VerticalJustification Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला भाग बेसलाइन पर रहता है |

### संबंधित देखें
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathFraction`](/slides/python-net/hi/aspose.slides.mathtext/mathfraction)
* enumeration [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)