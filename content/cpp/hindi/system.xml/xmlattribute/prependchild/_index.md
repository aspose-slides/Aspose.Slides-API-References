---
title: PrependChild()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट नोड को इस नोड के चाइल्ड नोड्स की सूची की शुरुआत में जोड़ता है।
type: docs
weight: 261
url: /hi/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) विधि


निर्दिष्ट नोड को इस नोड के चाइल्ड नोड्स की सूची की शुरुआत में जोड़ता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) जोड़ने के लिए। यदि यह एक [XmlDocumentFragment](../../xmldocumentfragment/) है, तो दस्तावेज़ अंश की पूरी सामग्री इस नोड की चाइल्ड सूची में स्थानांतरित हो जाती है। |

### रिटर्न मान

[XmlNode](../../xmlnode/) जोड़ा गया।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlAttribute](../)
* नेमस्पेस [System::Xml](../../)
* Library [Aspose.Slides](../../../)