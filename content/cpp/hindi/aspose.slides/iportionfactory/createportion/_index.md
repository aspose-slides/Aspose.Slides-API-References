---
title: CreatePortion()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक खाली पाठ भाग बनाता है।
type: docs
weight: 1
url: /hi/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() विधि

एक खाली पाठ भाग बनाता है।

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### वापसी मान

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) विधि

निर्दिष्ट स्ट्रिंग से एक पाठ भाग बनाता है।

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | स्ट्रिंग। |

### वापसी मान

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) विधि

निर्दिष्ट भाग डेटा का उपयोग करके एक भाग बनाता है।

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | उपयोग करने के लिए एक भाग। |

### वापसी मान

[Portion](../../portion/).

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPortion](../../iportion/)
* क्लास [IPortionFactory](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)