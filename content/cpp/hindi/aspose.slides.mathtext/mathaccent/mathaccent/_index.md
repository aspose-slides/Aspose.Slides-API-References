---
title: MathAccent()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट गणितीय तत्व पर लागू होने वाला गणितीय एक्सेंट बनाता है, जिसमें डिफ़ॉल्ट एक्सेंट अक्षर मान होता है
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) कंस्ट्रक्टर

निर्दिष्ट गणितीय तत्व पर लागू होने वाला गणितीय एक्सेंट बनाता है, जिसमें डिफ़ॉल्ट एक्सेंट अक्षर मान होता है

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | एक्सेंट लागू करने के लिए गणितीय तत्व |
## टिप्पणियाँ

उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) कंस्ट्रक्टर

निर्दिष्ट गणितीय तत्व पर लागू होने वाला गणितीय एक्सेंट बनाता है

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | एक्सेंट लागू करने के लिए गणितीय तत्व |
| accentCharacter | char16_t | एक्सेंट अक्षर |
## टिप्पणियाँ

उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathAccent](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)