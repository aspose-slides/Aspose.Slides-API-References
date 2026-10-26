---
title: GetAttribute()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट नाम वाले एट्रिब्यूट का मान लौटाता है।
type: docs
weight: 287
url: /hi/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) विधि

निर्दिष्ट नाम वाले एट्रिब्यूट का मान लौटाता है।

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का योग्य नाम। |

### वापसी मान

निर्दिष्ट एट्रिब्यूट का मान। यदि एट्रिब्यूट नहीं मिला, तो **nullptr** लौटाया जाता है।

## XmlNodeReader::GetAttribute(String, String) विधि

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रिब्यूट का मान लौटाता है।

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | एट्रिब्यूट का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | एट्रिब्यूट का नेमस्पेस URI। |

### वापसी मान

निर्दिष्ट एट्रिब्यूट का मान। यदि एट्रिब्यूट नहीं मिला, तो **nullptr** लौटाया जाता है।

## XmlNodeReader::GetAttribute(int32_t) विधि

निर्दिष्ट अनुक्रमांक वाले एट्रिब्यूट का मान लौटाता है।

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| attributeIndex | **int32_t** | एट्रिब्यूट का अनुक्रमांक। यह शून्य-आधारित है। (पहले एट्रिब्यूट का अनुक्रमांक 0 है।) |

### वापसी मान

निर्दिष्ट एट्रिब्यूट का मान।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)