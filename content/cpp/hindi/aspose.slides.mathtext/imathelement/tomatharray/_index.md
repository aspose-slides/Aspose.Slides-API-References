---
title: ToMathArray()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक लंबवत ऐरे में रखता है
type: docs
weight: 183
url: /hi/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() विधि


एक लंबवत ऐरे में रखता है

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### रिटर्न वैल्यू

प्रकार [IMathArray](../../imatharray/) का नया उदाहरण
## टिप्पणियाँ



उदाहरण: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathArray](../../imatharray/)
* क्लास [IMathElement](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)