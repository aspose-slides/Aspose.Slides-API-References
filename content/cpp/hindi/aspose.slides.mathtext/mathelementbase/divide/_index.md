---
title: Divide()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) मेथड

इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | हर |

### वापसी मान

नया भिन्न
## टिप्पणियाँ



उदाहरण: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) मेथड

इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | हर |

### वापसी मान

नया भिन्न
## टिप्पणियाँ



उदाहरण: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) मेथड

इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ निर्दिष्ट प्रकार का एक भिन्न बनाता है

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | हर |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | भिन्न प्रकार: Bar, NoBar, Skewed, Linear |

### वापसी मान

नया भिन्न
## टिप्पणियाँ



उदाहरण: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) मेथड

इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ निर्दिष्ट प्रकार का एक भिन्न बनाता है

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | हर |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | भिन्न प्रकार: Bar, NoBar, Skewed, Linear |

### वापसी मान

नया भिन्न
## टिप्पणियाँ



उदाहरण: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## संबंधित देखें

* एनम [MathFractionTypes](../../mathfractiontypes/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathFraction](../../imathfraction/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathElementBase](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)