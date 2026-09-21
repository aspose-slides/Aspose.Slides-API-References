---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides पाइथन के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
जब बुलेट सक्षम हो (जैसे PowerPoint में पैराग्राफ बुलेट/नंबरिंग सक्षम करने पर होता है) तो प्रभावी पैराग्राफ Indent और MarginLeft के लिए डिफ़ॉल्ट गैर-शून्य शिफ्ट सेट करता है। यदि बुलेट अक्षम हो तो केवल पैराग्राफ Indent और MarginLeft को रीसेट करता है (जैसे PowerPoint में पैराग्राफ बुलेट/नंबरिंग अक्षम करने पर होता है)। शिफ्ट को वर्तमान बुलेट संदर्भ - IBulletFormat.Type, .NumberedBulletStyle और पहले भाग की FontHeight - के अनुसार लागू किया जाता है। गैर-शून्य शिफ्ट को वर्तमान पैराग्राफ के प्रभावी Indent और MarginLeft पर लागू किया जाता है (परिणाम मान स्थानीय मान बनाते हैं)।

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | इस मेथड को कॉल करने से कोई असर नहीं पड़ता और निम्नलिखित मामलों में **System.InvalidOperationException** फेंकेगा:<br/>            यदि पैरेंट फॉर्मेटेड ऑब्जेक्ट पैराग्राफ नहीं है (उदाहरण के लिए ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() कॉल करने पर अपवाद फेंकेगा);<br/>            या यदि पैराग्राफ को किसी भी ITextFrame.Paragraphs संग्रह में नहीं जोड़ा गया है (पहले इसे जोड़ें); |

### देखें भी
* क्लास [`IBulletFormat`](/slides/python-net/hi/aspose.slides/ibulletformat)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)