---
title: set_LimitLocation()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सीमाओं का स्थान (सबस्क्रिप्ट और सुपरसक्रिप्ट)
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) विधि

सीमाओं का स्थान (सबस्क्रिप्ट और सुपरसक्रिप्ट)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## देखें

* एन्यूम [MathLimitLocations](../../mathlimitlocations/)
* क्लास [IMathNaryOperatorProperties](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)