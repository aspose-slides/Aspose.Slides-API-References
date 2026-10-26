---
title: Divide()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) विधि


इस अंश के साथ एक भिन्न बनाता है और निर्दिष्ट हर

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | हर |

### वापसी मान

नया भिन्न
## टिप्पणी



उदाहरण: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) विधि


इस अंश के साथ एक भिन्न बनाता है और निर्दिष्ट हर

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | हर |

### वापसी मान

नया भिन्न
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) विधि


इस अंश के साथ निर्दिष्ट प्रकार का भिन्न बनाता है और निर्दिष्ट हर

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | हर |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type: Bar, NoBar, Skewed, Linear |

### वापसी मान

नया भिन्न
## टिप्पणी



उदाहरण: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) विधि


इस अंश के साथ निर्दिष्ट प्रकार का भिन्न बनाता है और निर्दिष्ट हर

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | हर |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type: Bar, NoBar, Skewed, Linear |

### वापसी मान

नया भिन्न
## टिप्पणी



उदाहरण: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## और देखें

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)