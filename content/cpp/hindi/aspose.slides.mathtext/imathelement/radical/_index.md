---
title: Radical()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट तर्क से दिये गये डिग्री का गणितीय मूल निर्धारित करता है।
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) विधि

दिए गए डिग्री का गणितीय मूल निर्दिष्ट तर्क से निर्धारित करता है।

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Radical का तर्क |

### रिटर्न मान

प्रकार [IMathRadical](../../imathradical/) की नई इंस्टेंस

## टिप्पणियाँ

उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) विधि

दिए गए डिग्री का गणितीय मूल निर्दिष्ट तर्क से निर्धारित करता है।

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Radical का तर्क |

### रिटर्न मान

प्रकार [IMathRadical](../../imathradical/) की नई इंस्टेंस

## टिप्पणियाँ

उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## संदर्भ

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRadical](../../imathradical/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)