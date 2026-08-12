---
title: SetLowerLimit()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निचली सीमा लेता है
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) विधि


निचली सीमा लेता है

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### वापसी मान

प्रकार [IMathLimit](../../imathlimit/) का नया उदाहरण
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) विधि


निचली सीमा लेता है

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### वापसी मान

प्रकार [IMathLimit](../../imathlimit/) का नया उदाहरण
## टिप्पणियाँ



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathLimit](../../imathlimit/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathElementBase](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)