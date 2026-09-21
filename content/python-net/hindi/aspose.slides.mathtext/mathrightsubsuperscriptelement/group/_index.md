---
title: group method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रेस्केट का उपयोग करके एक समूह में रखता है

### वापसी

प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) की नई इंस्टेंस



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह बनाने वाले अक्षर जैसे नीचे की कर्ली ब्रेस्केट या कोई अन्य का उपयोग करके एक समूह में रखता है

### वापसी

प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter) की नई इंस्टेंस



```python
def group(self, character, position, vertical_justification):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूह बनाने वाला अक्षर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह बनाने वाले अक्षर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | ग्रुप अक्षर की वर्टिकल जस्टिफिकेशन।<br/><br/>ऑब्जेक्ट की बेसलाइन के संबंध में संरेखण निर्धारित करता है।<br/><br/>उदाहरण के लिए, जब ग्रुप अक्षर ऑब्जेक्ट के ऊपर होता है, <br/><br/>Top का VerticalJustification दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर आता है;<br/><br/>जब VerticalJustification Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला भाग बेसलाइन पर रहता है |



### संबंधित देखें
* क्लास [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* क्लास [`MathRightSubSuperscriptElement`](/slides/python-net/hi/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)