---
title: MathBox()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट तत्व को तर्क के रूप में लेकर MathBox को प्रारम्भ करता है
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) कन्स्ट्रक्टर


निर्दिष्ट तत्व को तर्क के रूप में लेकर [MathBox](../) को आरम्भ करता है

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बॉक्स जिस मूल तत्व पर लागू है। यह null हो सकता है। |
## टिप्पणी



उदाहरण: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## संदर्भ देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBox](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)