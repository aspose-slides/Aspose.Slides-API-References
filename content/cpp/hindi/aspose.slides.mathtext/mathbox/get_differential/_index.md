---
title: get_Differential()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Differential जब true हो, बॉक्स differential के रूप में कार्य करता है (उदाहरण के लिए \\uD835\\uDC51\\uD835\\uDC65 एक integrand में), और गणितीय differential के लिए उचित क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false"
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() विधि

Differential जब true हो, बॉक्स differential के रूप में कार्य करता है (उदाहरण के लिए \\uD835\\uDC51\\uD835\\uDC65 एक integrand में), और गणितीय differential के लिए उचित क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## संबंधित देखें

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)