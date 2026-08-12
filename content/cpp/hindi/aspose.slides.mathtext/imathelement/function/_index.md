---
title: Function()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके आर्ग्युमेंट का फ़ंक्शन लेता है
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) मेथड


इस इंस्टेंस का उपयोग फ़ंक्शन नाम के रूप में करके एक आर्ग्युमेंट का फ़ंक्शन लेता है

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | फ़ंक्शन का एक आर्ग्युमेंट |

### रिटर्न वैल्यू

प्रकार [IMathFunction](../../imathfunction/) का नया गणितीय तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) मेथड


इस इंस्टेंस का उपयोग फ़ंक्शन नाम के रूप में करके एक आर्ग्युमेंट का फ़ंक्शन लेता है

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | फ़ंक्शन का एक आर्ग्युमेंट |

### रिटर्न वैल्यू

प्रकार [IMathFunction](../../imathfunction/) का नया गणितीय तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)