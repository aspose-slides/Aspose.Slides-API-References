---
title: set_LimitLocation()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सीमाओं का स्थान (उपस्क्रिप्ट और सुपरस्क्रिप्ट)
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) विधि

सीमाओं का स्थान (उपस्क्रिप्ट और सुपरस्क्रिप्ट)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## संबंधित देखें

* एनम [MathLimitLocations](../../mathlimitlocations/)
* क्लास [MathNaryOperator](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)