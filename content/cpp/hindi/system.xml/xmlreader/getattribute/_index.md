---
title: GetAttribute()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट XmlReader::get_Name मान वाले एट्रिब्यूट का मान प्राप्त करता है."
type: docs
weight: 599
url: /hi/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) मेथड

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_Name](../get_name/) मान वाले एट्रिब्यूट का मान प्राप्त करता है।

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का योग्य नाम। |

### रिटर्न वैल्यू

निर्दिष्ट एट्रिब्यूट का मान। यदि एट्रिब्यूट नहीं मिला या मान [String::Empty](../../../system/string/empty/) है, तो **nullptr** लौटाया जाता है।

## XmlReader::GetAttribute(String, String) मेथड

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_LocalName](../get_localname/) और [XmlReader::get_NamespaceURI](../get_namespaceuri/) मान वाले एट्रिब्यूट का मान प्राप्त करता है।

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |

### रिटर्न वैल्यू

निर्दिष्ट एट्रिब्यूट का मान। यदि एट्रिब्यूट नहीं मिला या मान [String::Empty](../../../system/string/empty/) है, तो **nullptr** लौटाया जाता है। यह मेथड रीडर को नहीं घुमाता है।

## XmlReader::GetAttribute(int32_t) मेथड

जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट क्रमांक वाले एट्रिब्यूट का मान प्राप्त करता है।

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | **int32_t** | एट्रिब्यूट का क्रमांक। क्रमांक शून्य-आधारित है। (पहले एट्रिब्यूट का क्रमांक 0 है।) |

### रिटर्न वैल्यू

निर्दिष्ट एट्रिब्यूट का मान। यह मेथड रीडर को नहीं घुमाता है।

## भी देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)