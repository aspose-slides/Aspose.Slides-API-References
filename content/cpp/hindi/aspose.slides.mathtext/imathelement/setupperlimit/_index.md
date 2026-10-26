---
title: SetUpperLimit()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऊपरी सीमा लेता है
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) विधि

ऊपरी सीमा लेता है

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### रिटर्न मान

प्रकार [IMathLimit](../../imathlimit/) की नई इंस्टेंस

## टिप्पणियाँ


उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) विधि

ऊपरी सीमा लेता है

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### रिटर्न मान

प्रकार [IMathLimit](../../imathlimit/) की नई इंस्टेंस

## टिप्पणियाँ


उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathLimit](../../imathlimit/)
* क्लास [IMathElement](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)