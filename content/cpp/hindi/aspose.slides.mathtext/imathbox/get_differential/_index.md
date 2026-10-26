---
title: get_Differential()
second_title: Aspose.Slides for C++ API संदर्भ
description: "डिफ़रेंशियल। जब true हो, बॉक्स एक डिफ़रेंशियल (उदा., \\uD835\\uDC51\\uD835\\uDC65 एक integrand में) की तरह कार्य करता है, और गणितीय डिफ़रेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false"
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() मेथड

Differential. जब true हो, बॉक्स एक differential (उदाहरण के लिए, \\uD835\\uDC51\\uD835\\uDC65 एक integrand में) की तरह कार्य करता है, और गणितीय differential के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## और देखें

* क्लास [IMathBox](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)