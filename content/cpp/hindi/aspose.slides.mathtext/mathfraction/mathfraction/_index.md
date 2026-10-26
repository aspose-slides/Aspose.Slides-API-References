---
title: MathFraction()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट अंशांक, हर और प्रकार के साथ MathFraction को प्रारंभ करता है
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/mathfraction/mathfraction/
---
## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) कंस्ट्रक्टर

[MathFraction](../) को निर्दिष्ट अंशांक, हर और प्रकार के साथ आरम्भ करता है

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | अंशांक |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | हर |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | अंश प्रकार |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"), MathFractionTypes::Linear);
```

## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) कंस्ट्रक्टर

'Bar' प्रकार के एक [MathFraction](../) को निर्दिष्ट अंशांक और हर के साथ आरम्भ करता है

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | अंशांक |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | हर |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"));
```

## संबंधित देखें

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)