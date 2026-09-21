---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
जब bullets सक्षम हो तो प्रभावी पैराग्राफ Indent और MarginLeft के लिए डिफ़ॉल्ट गैर-शून्य शिफ्ट सेट करता है (जैसा कि PowerPoint पैराग्राफ bullets/numbering सक्षम करने पर करता है)। यदि bullets अक्षम है तो केवल पैराग्राफ Indent और MarginLeft को रीसेट करता है (जैसा कि PowerPoint पैराग्राफ bullets/numbering अक्षम करने पर करता है)। Indent शिफ्ट वर्तमान bullet संदर्भ - IBulletFormat.Type, .NumberedBulletStyle और प्रथम भाग के FontHeight - के अनुसार लागू होते हैं। गैर-शून्य indent शिफ्ट वर्तमान पैराग्राफ के प्रभावी Indent और MarginLeft पर लागू होते हैं (परिणामी मान स्थानीय मान बनते हैं)।

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | इस मेथड को कॉल करने से कोई फर्क नहीं पड़ता और निम्न मामलों में **System.InvalidOperationException** फेंकता है:<br/>            यदि पैरेंट फ़ॉर्मेटेड ऑब्जेक्ट पैराग्राफ नहीं है (उदाहरण के लिए ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() को कॉल करने पर अपवाद फेंकेगा);<br/>            या यदि पैराग्राफ को किसी भी ITextFrame.Paragraphs संग्रह में नहीं जोड़ा गया है (पहले इसे जोड़ें); |

### देखें

* क्लास [`BulletFormat`](/slides/python-net/hi/aspose.slides/bulletformat)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)