---
title: set_DelimiterShape()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "डिलिमीटर ऑब्जेक्ट में डिलिमीटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape::Centered है, तो डिलिमीटर गणितीय पाठ के गणित अक्ष के चारों ओर केंद्रित होते हैं और उनकी सामग्री की पूरी ऊँचाई में फिट होने के लिए बनाए रखा जाता है। जब MathDelimiterShape::Match है, तो उनकी ऊँचाई और आकार ठीक उनकी सामग्री से मेल खाने के लिए बदले जाते हैं।"
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) मेथड

डिलिमीटर ऑब्जेक्ट में डिलिमीटर के आकार को निर्दिष्ट करता है। जब [MathDelimiterShape::Centered](../../mathdelimitershape/) है, तो डिलिमीटर गणितीय पाठ के गणित अक्ष के चारों ओर केंद्रित होते हैं और उनके सामग्री की पूरी ऊँचाई में फिट होने के लिए बनाए रखते हैं। जब [MathDelimiterShape::Match](../../mathdelimitershape/) है, तो उनकी ऊँचाई और आकार ठीक से उनकी सामग्री से मेल खाने के लिए बदले जाते हैं।

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## और देखें

* एन्यूम [MathDelimiterShape](../../mathdelimitershape/)
* क्लास [MathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)