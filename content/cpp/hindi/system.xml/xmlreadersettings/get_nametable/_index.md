---
title: get_NameTable()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एटॉमाइज़्ड स्ट्रिंग तुलना के लिए उपयोग किए जाने वाले XmlNameTable को लौटाता है।
type: docs
weight: 1
url: /hi/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() मेथड

वापिस देता है [XmlNameTable](../../xmlnametable/) जिसका उपयोग एटॉमाइज़्ड स्ट्रिंग तुलना के लिए किया जाता है।

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### रिटर्न वैल्यू

The [XmlNameTable](../../xmlnametable/) जो सभी एटॉमाइज़्ड स्ट्रिंग्स को संग्रहित करता है जो सभी [XmlReader](../../xmlreader/) इंस्टेंसेज़ द्वारा इस [XmlReaderSettings](../) ऑब्जेक्ट का उपयोग करके निर्मित होते हैं। डिफ़ॉल्ट **nullptr** है। निर्मित [XmlReader](../../xmlreader/) इंस्टेंस नई खाली [NameTable](../../nametable/) का उपयोग करेगा यदि यह मान **nullptr** है।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNameTable](../../xmlnametable/)
* क्लास [XmlReaderSettings](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)