---
title: MoveToAttribute()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट XmlReader::get_Name मान वाले एट्रिब्यूट पर जाता है।"
type: docs
weight: 625
url: /hi/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) विधि

जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_Name](../get_name/) मान वाले एट्रिब्यूट पर जाता है।

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का योग्य नाम। |

### रिटर्न मान

**true** यदि एट्रिब्यूट मिला है; अन्यथा, **false**। यदि **false**, रीडर की स्थिति नहीं बदलती है।

## XmlReader::MoveToAttribute(String, String) विधि

जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_LocalName](../get_localname/) और [XmlReader::get_NamespaceURI](../get_namespaceuri/) मान वाले एट्रिब्यूट पर जाता है।

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का स्थानीय नाम। |
| ns | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |

### रिटर्न मान

**true** यदि एट्रिब्यूट मिला है; अन्यथा, **false**। यदि **false**, रीडर की स्थिति नहीं बदलती है।

## XmlReader::MoveToAttribute(int32_t) विधि

जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट अनुक्रमांक वाले एट्रिब्यूट पर जाता है।

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | **int32_t** | एट्रिब्यूट का अनुक्रमांक। |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)