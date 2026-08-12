---
title: GetAttribute()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट नाम वाले गुणधर्म का मान लौटाता है।
type: docs
weight: 495
url: /hi/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) विधि

निर्दिष्ट नाम वाले गुणधर्म का मान लौटाता है।

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | गुणधर्म का योग्य नाम। |

### वापसी मान

निर्दिष्ट गुणधर्म का मान। यदि गुणधर्म नहीं मिला, तो **nullptr** लौटाया जाता है।

## XmlTextReader::GetAttribute(String, String) विधि

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले गुणधर्म का मान लौटाता है।

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | गुणधर्म का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | गुणधर्म का नेमस्पेस URI। |

### वापसी मान

निर्दिष्ट गुणधर्म का मान। यदि गुणधर्म नहीं मिला, तो **nullptr** लौटाया जाता है। यह विधि रीडर को नहीं ले जाती है।

## XmlTextReader::GetAttribute(int32_t) विधि

निर्दिष्ट अनुक्रमांक वाले गुणधर्म का मान लौटाता है।

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | **int32_t** | गुणधर्म का अनुक्रमांक। अनुक्रमांक शून्य-आधारित है। (पहला गुणधर्म का अनुक्रमांक 0 है।) |

### वापसी मान

निर्दिष्ट गुणधर्म का मान।

## संबंधित

* क्लास [String](../../../system/string/)
* क्लास [XmlTextReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)