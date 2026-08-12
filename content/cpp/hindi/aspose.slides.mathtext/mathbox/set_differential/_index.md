---
title: set_Differential()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "डिफरेंशियल जब true हो, बॉक्स डिफरेंशियल के रूप में कार्य करता है (उदाहरण के लिए, \\uD835\\uDC51\\uD835\\uDC65 एक इंटीग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false"
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) विधि


डिफरेंशियल जब true हो, बॉक्स डिफरेंशियल के रूप में कार्य करता है (उदाहरण के लिए, \\uD835\\uDC51\\uDC65 एक इंटीग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## टिप्पणी


उदाहरण: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## देखें

* क्लास [MathBox](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)