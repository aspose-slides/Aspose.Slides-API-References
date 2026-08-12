---
title: get_DelimiterShape()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape::Centered होता है, तो डिलिमिटर गणितीय पाठ के गणितीय अक्ष के चारों ओर केंद्रित होते हैं और उनकी सामग्री की पूरी ऊँचाई में फिट होने के लिए बनाए रखते हैं। जब MathDelimiterShape::Match होता है, तो उनकी ऊँचाई और आकार बिल्कुल उनकी सामग्री से मेल खाने के लिए बदल दिया जाता है।"
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() विधि


डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब [MathDelimiterShape::Centered](../../mathdelimitershape/) हो, तो डिलिमिटर गणितीय पाठ के गणितीय अक्ष के चारों ओर केंद्रीकृत होते हैं और उनके सामग्री की पूरी ऊँचाई में फिट होने के लिए बनाए रखे जाते हैं। जब [MathDelimiterShape::Match](../../mathdelimitershape/) हो, तो उनकी ऊँचाई और आकार बिल्कुल उनकी सामग्री से मेल खाने के लिए बदल दिए जाते हैं।

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## टिप्पणी


उदाहरण: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## देखें

* एनम [MathDelimiterShape](../../mathdelimitershape/)
* क्लास [IMathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)