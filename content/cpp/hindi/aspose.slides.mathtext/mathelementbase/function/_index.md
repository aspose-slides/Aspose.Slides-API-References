---
title: Function()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस instance को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) विधि

इस instance को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | फ़ंक्शन का तर्क |

### रिटर्न मान

प्रकार [IMathFunction](../../imathfunction/) का नया गणित तत्व

## टिप्पणियाँ

उदाहरण: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) विधि

इस instance को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | फ़ंक्शन का तर्क |

### रिटर्न मान

प्रकार [IMathFunction](../../imathfunction/) का नया गणित तत्व

## टिप्पणियाँ

उदाहरण: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathFunction](../../imathfunction/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathElementBase](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)