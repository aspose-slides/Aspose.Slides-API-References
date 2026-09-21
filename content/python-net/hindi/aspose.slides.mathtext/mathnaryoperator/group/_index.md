---
title: group method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/mathnaryoperator/group/
weight: 80
---
## group(self) {#}
इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके समूह में रखता है

### रिटर्न
नई प्रकार की इंस्टेंस [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
इस तत्व को समूह चरित्र जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करके समूह में रखता है

### रिटर्न
नई प्रकार की इंस्टेंस [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| character | **char** | समूह चरित्र जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह चरित्र की स्थिति |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions) | समूह चरित्र का ऊर्ध्वाधर संरेखण।<br/><br/>            वस्तु के बेसलाइन के सापेक्ष वस्तु के संरेखण को निर्दिष्ट करता है।<br/><br/>            उदाहरण के लिए, जब समूह चरित्र वस्तु के ऊपर हो, <br/><br/>            Top का VerticalJustification इंगित करता है कि वस्तु का शीर्ष बेसलाइन पर है;<br/><br/>            जब VerticalJustification Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है |

### देखें
* कक्षा [`IMathGroupingCharacter`](/slides/python-net/hi/aspose.slides.mathtext/imathgroupingcharacter)
* कक्षा [`MathNaryOperator`](/slides/python-net/hi/aspose.slides.mathtext/mathnaryoperator)
* एन्यूमरेशन [`MathTopBotPositions`](/slides/python-net/hi/aspose.slides.mathtext/mathtopbotpositions)
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)