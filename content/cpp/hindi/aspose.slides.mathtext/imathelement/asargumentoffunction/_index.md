---
title: AsArgumentOfFunction()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) विधि

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | फ़ंक्शन नाम |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) का नया गणितीय तत्व

## टिप्पणी



उदाहरण: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) विधि

इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | फ़ंक्शन नाम |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) का नया गणितीय तत्व

## टिप्पणी



उदाहरण: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) विधि


इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | एक तर्क के सामान्य फ़ंक्शन प्रकारों में से एक |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) का नया गणितीय तत्व

## टिप्पणी



उदाहरण: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) विधि


इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क निर्दिष्ट करता है

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | दो तर्कों में से एक सामान्य फ़ंक्शन प्रकार: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | फ़ंक्शन प्रकार के आधार पर अतिरिक्त तर्क |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) का नया गणितीय तत्व

## टिप्पणी



उदाहरण: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 'x' का लॉगरिद्म बेस '5' पर लौटाता है
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) विधि


इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त तर्क निर्दिष्ट करता है

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | दो तर्कों में से एक सामान्य फ़ंक्शन प्रकार: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | फ़ंक्शन प्रकार के आधार पर अतिरिक्त तर्क |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) का नया गणितीय तत्व

## टिप्पणी



उदाहरण: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 'x' का लॉगरिद्म बेस '5' पर लौटाता है
```

## संबंधित देखें

* एनम [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* एनम [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathFunction](../../imathfunction/)
* क्लास [IMathElement](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)