---
title: get_LocalName()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब डेरिव्ड क्लास में ओवरराइड किया जाता है, तो यह वर्तमान नोड का स्थानीय नाम प्राप्त करता है।
type: docs
weight: 40
url: /hi/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() विधि


When overridden in a derived class, gets the local name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### रिटर्न वैल्यू

The name of the current node with the prefix removed. For example, **LocalName** is **book** for the element **<bk:book>**. For node types that do not have a name (like **[Text](../../../system.text/)**, **Comment**, and so on), this method returns [String::Empty](../../../system/string/empty/).

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)