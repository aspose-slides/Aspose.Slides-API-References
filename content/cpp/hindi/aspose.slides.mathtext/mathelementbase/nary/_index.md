---
title: Nary()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: एक N-ary ऑपरेटर बनाता है
type: docs
weight: 157
url: /hi/aspose.slides.mathtext/mathelementbase/nary/
---
## MathElementBase::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


एक N-ary ऑपरेटर बनाता है

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The upper limit |

### रिटर्न वैल्यू

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"i-1");
auto lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
auto upperLimit = System::MakeObject<MathematicalText>(u"\U0001d465");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## MathElementBase::Nary(MathNaryOperatorTypes, System::String, System::String) method


एक N-ary ऑपरेटर बनाता है

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit) override
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::String](../../../system/string/) | The lower limit |
| upperLimit | [System::String](../../../system/string/) | The upper limit |

### रिटर्न वैल्यू

New instance of type [IMathNaryOperator](../../imathnaryoperator/)
## टिप्पणियाँ



उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d465");
```

## संबंधित देखें

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)