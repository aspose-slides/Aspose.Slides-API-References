---
title: idx_get()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का मान प्राप्त करता है।
type: docs
weight: 612
url: /hi/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) विधि

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का मान प्राप्त करता है।

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | **int32_t** | एट्रिब्यूट का इंडेक्स। |

### रिटर्न मान

निर्दिष्ट एट्रिब्यूट का मान।

## XmlReader::idx_get(String) विधि

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_Name](../get_name/) मान वाले एट्रिब्यूट का मान प्राप्त करता है।

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का योग्य नाम। |

### रिटर्न मान

निर्दिष्ट एट्रिब्यूट का मान। यदि एट्रिब्यूट नहीं मिला है, तो **nullptr** लौटाया जाता है।

## XmlReader::idx_get(String, String) विधि

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_LocalName](../get_localname/) और [XmlReader::get_NamespaceURI](../get_namespaceuri/) मान वाले एट्रिब्यूट का मान प्राप्त करता है।

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |

### रिटर्न मान

निर्दिष्ट एट्रिब्यूट का मान। यदि एट्रिब्यूट नहीं मिला है, तो **nullptr** लौटाया जाता है।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)