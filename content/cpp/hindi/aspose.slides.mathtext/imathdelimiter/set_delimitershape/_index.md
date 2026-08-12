---
title: set_DelimiterShape()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: "डिलिमीटर ऑब्जेक्ट में डिलिमीटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape::Centered होता है, तो डिलिमीटर गणितीय पाठ के गणितीय अक्ष के चारों ओर केंद्रित होते हैं और उनकी सामग्री की पूरी ऊँचाई में फिट होने के लिए बनाये रखे जाते हैं। जब MathDelimiterShape::Match होता है, तो उनकी ऊँचाई और आकार को बिल्कुल उनकी सामग्री से मेल खाने के लिए बदल दिया जाता है।"
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) विधि

डिलिमीटर ऑब्जेक्ट में डिलिमीटर के आकार को निर्दिष्ट करता है। जब [MathDelimiterShape::Centered](../../mathdelimitershape/) है, तो डिलिमीटर गणितीय पाठ के गणितीय अक्ष के चारों ओर केंद्रित होते हैं और उनके सामग्री की पूरी ऊँचाई में फिट होने के लिए बनाए रखे जाते हैं। जब [MathDelimiterShape::Match](../../mathdelimitershape/) है, तो उनकी ऊँचाई और आकार को बिल्कुल उनके सामग्री के अनुरूप बदल दिया जाता है।

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## संबंधित देखें

* एनम [MathDelimiterShape](../../mathdelimitershape/)
* क्लास [IMathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)