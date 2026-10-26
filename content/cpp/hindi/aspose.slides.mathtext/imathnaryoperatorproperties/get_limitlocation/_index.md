---
title: get_LimitLocation()
second_title: Aspose.Slides for C++ API संदर्भ
description: सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() विधि

सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## संबंधित देखें

* Enum [MathLimitLocations](../../mathlimitlocations/)
* क्लास [IMathNaryOperatorProperties](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)