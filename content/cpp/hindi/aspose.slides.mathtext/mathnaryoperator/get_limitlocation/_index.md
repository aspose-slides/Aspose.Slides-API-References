---
title: get_LimitLocation()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() विधि


सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## देखें

* एनम [MathLimitLocations](../../mathlimitlocations/)
* क्लास [MathNaryOperator](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)