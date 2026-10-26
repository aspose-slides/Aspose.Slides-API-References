---
title: group method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/matharray/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की घुमावदार ब्रैकेट का उपयोग करके समूह में रखता है

### Returns
वापसी

नई instance प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह में रखने के लिये एक समूह बनाता हुआ कैरेक्टर जैसे नीचे की घुमावदार ब्रैकेट या कोई अन्य उपयोग करता है

### Returns
वापसी

नई instance प्रकार [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| character | **char** | समूह बनाने वाला कैरेक्टर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह बनाते हुए कैरेक्टर की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह कैरेक्टर का ऊर्ध्वाधर न्याय।<br/><br/>            वस्तु के बेसलाइन संबंधी संरेखण को निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिये, जब समूह कैरेक्टर वस्तु के ऊपर होता है, <br/><br/>            Top की VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर है;<br/><br/>            जब VerticalJustification Bottom पर सेट किया जाता है, वस्तु का निचला भाग बेसलाइन पर रहता है |



### See Also
* class [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* class [`MathArray`](/slides/python-net/hi/aspose.slides.mathtext/matharray)
* enumeration [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* module [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)