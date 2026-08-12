---
title: Integral()
second_title: Aspose.Slides for C++ API संदर्भ
description: समाकल लेता है
type: docs
weight: 196
url: /hi/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) विधि

समाकल लेता है

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | समाकल प्रकार |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | समाकल की निचली सीमा |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | समाकल की ऊपरी सीमा |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | सीमाओं का स्थान |

### वापसी मान

प्रकार [IMathNaryOperator](../../imathnaryoperator/) का नया इंस्टेंस
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) विधि

समाकल लेता है

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | समाकल प्रकार |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | समाकल की निचली सीमा |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | समाकल की ऊपरी सीमा |

### वापसी मान

प्रकार [IMathNaryOperator](../../imathnaryoperator/) का नया इंस्टेंस
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) विधि

समाकल लेता है बिना सीमाओं के

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | समाकल प्रकार |

### वापसी मान

प्रकार [IMathNaryOperator](../../imathnaryoperator/) का नया इंस्टेंस
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) विधि

समाकल लेता है

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | समाकल प्रकार |
| lowerLimit | [System::String](../../../system/string/) | समाकल की निचली सीमा |
| upperLimit | [System::String](../../../system/string/) | समाकल की ऊपरी सीमा |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | सीमाओं का स्थान |

### वापसी मान

प्रकार [IMathNaryOperator](../../imathnaryoperator/) का नया इंस्टेंस
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) विधि

समाकल लेता है

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | समाकल प्रकार |
| lowerLimit | [System::String](../../../system/string/) | समाकल की निचली सीमा |
| upperLimit | [System::String](../../../system/string/) | समाकल की ऊपरी सीमा |

### वापसी मान

प्रकार [IMathNaryOperator](../../imathnaryoperator/) का नया इंस्टेंस
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## अन्य देखें

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* वर्ग [IMathNaryOperator](../../imathnaryoperator/)
* वर्ग [IMathElement](../)
* वर्ग [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)