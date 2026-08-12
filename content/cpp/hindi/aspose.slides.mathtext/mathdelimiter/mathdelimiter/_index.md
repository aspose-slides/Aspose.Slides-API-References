---
title: MathDelimiter()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट तत्व को एकल बेस तर्क के रूप में उपयोग करके MathDelimiter को प्रारंभ करता है
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) निर्माता

[MathDelimiter](../) को निर्दिष्ट तत्व के साथ एकल बेस तर्क के रूप में प्रारंभ करता है

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | डिलिमिटर लागू किया जाने वाला मूल तत्व। यह null भी हो सकता है। |
## टिप्पणियां



उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)