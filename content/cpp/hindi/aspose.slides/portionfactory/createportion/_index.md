---
title: CreatePortion()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक खाली टेक्स्ट भाग बनाता है।
type: docs
weight: 1
url: /hi/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() विधि

एक खाली टेक्स्ट भाग बनाता है।

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### रिटर्न वैल्यू

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) विधि

निर्दिष्ट स्ट्रिंग से एक टेक्स्ट भाग बनाता है।

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | स्ट्रिंग। |

### रिटर्न वैल्यू

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) विधि

निर्दिष्ट भाग डेटा का उपयोग करके एक भाग बनाता है।

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | उपयोग के लिए एक भाग। |

### रिटर्न वैल्यू

[Portion](../../portion/).

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPortion](../../iportion/)
* क्लास [PortionFactory](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)