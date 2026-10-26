---
title: ToMathArray()
second_title: Aspose.Slides for C++ API संदर्भ
description: बच्चों तत्वों को एक लंबवत सरणी में रखता है
type: docs
weight: 235
url: /hi/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() विधि


बच्चे तत्वों को एक लंबवत सरणी में रखता है

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### रिटर्न वैल्यू

नया उदाहरण प्रकार [IMathArray](../../imatharray/)
## टिप्पणियां



उदाहरण: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathArray](../../imatharray/)
* क्लास [MathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)