---
title: get_DelimiterShape()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "डिलिमिटर ऑब्जेक्ट में डिलिमिटर्स के आकार को निर्दिष्ट करता है। जब MathDelimiterShape::Centered होता है, तो डिलिमिटर्स गणितीय पाठ के गणितीय अक्ष के आसपास केंद्रित होते हैं और उनकी सामग्री की पूरी ऊँचाई में फिट होने के लिए बनाए जाते हैं। जब MathDelimiterShape::Match होता है, तो उनकी ऊँचाई और आकार को बिल्कुल उनकी सामग्री से मेल खाने के लिए बदल दिया जाता है।"
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() method


डिलिमिटर ऑब्जेक्ट में डिलिमिटर्स के आकार को निर्दिष्ट करता है। जब [MathDelimiterShape::Centered](../../mathdelimitershape/) हो, तो डिलिमिटर्स गणितीय पाठ के गणितीय अक्ष के चारों ओर केंद्रित होते हैं और उनके सामग्री की पूरी ऊँचाई में फिट होने के लिए बनाई जाती हैं। जब [MathDelimiterShape::Match](../../mathdelimitershape/) हो, तो उनकी ऊँचाई और आकार को बिल्कुल उनके सामग्री के अनुरूप बदल दिया जाता है।

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Remarks


Example: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## See Also

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)