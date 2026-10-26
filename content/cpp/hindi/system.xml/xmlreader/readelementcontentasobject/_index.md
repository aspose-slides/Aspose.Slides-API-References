---
title: ReadElementContentAsObject()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान तत्व को पढ़ता है और उसकी सामग्री को एक ऑब्जेक्ट के रूप में लौटाता है।
type: docs
weight: 469
url: /hi/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() मेथड

वर्तमान तत्व को पढ़ता है और उसकी सामग्री को एक [Object](../../../system/object/) के रूप में लौटाता है।

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### रिटर्न वैल्यू

सबसे उपयुक्त प्रकार का बॉक्स्ड ऑब्जेक्ट। [XmlReader::get_ValueType](../get_valuetype/) मान उपयुक्त प्रकार निर्धारित करता है। यदि सामग्री को सूची प्रकार के रूप में टाइप किया गया है, तो यह मेथड उपयुक्त प्रकार के बॉक्स्ड ऑब्जेक्ट्स की एक एरे लौटाता है।

## XmlReader::ReadElementContentAsObject(String, String) मेथड

जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और उसकी सामग्री को एक [Object](../../../system/object/) के रूप में लौटाता है।

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### तर्क

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | तत्व का स्थानीय नाम। |
| namespaceURI | [String](../../../system/string/) | तत्व का नेमस्पेस URI। |

### रिटर्न वैल्यू

सबसे उपयुक्त प्रकार का बॉक्स्ड ऑब्जेक्ट। [XmlReader::get_ValueType](../get_valuetype/) मान उपयुक्त प्रकार निर्धारित करता है। यदि सामग्री को सूची प्रकार के रूप में टाइप किया गया है, तो यह मेथड उपयुक्त प्रकार के बॉक्स्ड ऑब्जेक्ट्स की एक एरे लौटाता है।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [XmlReader](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)