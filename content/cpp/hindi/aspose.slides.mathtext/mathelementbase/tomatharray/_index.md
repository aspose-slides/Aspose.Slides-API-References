---
title: ToMathArray()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक ऊर्ध्वाधर ऐरे में रखता है
type: docs
weight: 170
url: /hi/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() मेथड


एक ऊर्ध्वाधर एरे में रखता है

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### रिटर्न वैल्यू

[IMathArray](../../imatharray/) प्रकार का नया उदाहरण
## टिप्पणियाँ



उदाहरण: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathArray](../../imatharray/)
* क्लास [MathElementBase](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)