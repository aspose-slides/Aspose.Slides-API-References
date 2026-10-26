---
title: AsArgumentOfFunction()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) मेथड


इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | फ़ंक्शन नाम |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) वाला नया गणित तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) मेथड


इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | फ़ंक्शन नाम |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) वाला नया गणित तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) मेथड


इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | एक आर्ग्युमेंट वाले सामान्य फ़ंक्शन प्रकार में से एक |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) वाला नया गणित तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) मेथड


इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त आर्ग्युमेंट लेता है

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | दो आर्ग्युमेंट वाले सामान्य फ़ंक्शन प्रकार में से एक: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | फ़ंक्शन प्रकार के आधार पर अतिरिक्त आर्ग्युमेंट |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) वाला नया गणित तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// 'x' का लघुगणक बेस '5' पर लौटाता है
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) मेथड


इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त आर्ग्युमेंट लेता है

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | दो आर्ग्युमेंट वाले सामान्य फ़ंक्शन प्रकार में से एक: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | फ़ंक्शन प्रकार के आधार पर अतिरिक्त आर्ग्युमेंट |

### वापसी मान

प्रकार [IMathFunction](../../imathfunction/) वाला नया गणित तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// 'x' का लघुगणक बेस '5' पर लौटाता है
```

## देखें भी

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)