---
title: Radical()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है।
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) मेथड


निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है।

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument of Radical |

### वापसी मान

New instance of type [IMathRadical](../../imathradical/)
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) मेथड


निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है।

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### वापसी मान

New instance of type [IMathRadical](../../imathradical/)
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## संदर्भ

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathRadical](../../imathradical/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathElementBase](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)