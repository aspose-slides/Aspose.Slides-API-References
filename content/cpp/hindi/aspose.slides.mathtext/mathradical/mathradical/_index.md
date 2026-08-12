---
title: MathRadical()
second_title: Aspose.Slides for C++ API संदर्भ
description: MathRadical वर्ग का नया उदाहरण प्रारंभ करता है।
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) कन्स्ट्रक्टर

[MathRadical](../) वर्ग का नया उदाहरण प्रारंभ करता है।

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | आधार |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | डिग्री |
## टिप्पणियाँ

उदाहरण: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## संबंधित देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathRadical](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)