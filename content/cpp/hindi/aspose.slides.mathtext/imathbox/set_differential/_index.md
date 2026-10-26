---
title: set_Differential()
second_title: Aspose.Slides for C++ API संदर्भ
description: "अवकल। जब सत्य हो, बॉक्स एक अवकल के रूप में कार्य करता है (उदाहरण के लिए, \\uD835\\uDC51\\uD835\\uDC65 एक इंटीग्रैंड में), और गणितीय अवकल के लिए उपयुक्त क्षैतिज अंतराल प्राप्त करता है। डिफ़ॉल्ट: false"
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) विधि


अवकल। जब सत्य हो, बॉक्स एक अवकल के रूप में कार्य करता है (उदाहरण के लिए, \\uD835\\uDC51\\uD835\\uDC65 एक इंटीग्रैंड में), और गणितीय अवकल के लिए उपयुक्त क्षैतिज अंतराल प्राप्त करता है। डिफ़ॉल्ट: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
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

* कक्षा [IMathBox](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)