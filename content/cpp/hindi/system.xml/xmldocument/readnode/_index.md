---
title: ReadNode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XmlReader में जानकारी के आधार पर एक XmlNode ऑब्जेक्ट बनाता है। रीडर को किसी नोड या एट्रिब्यूट पर स्थित होना चाहिए।
type: docs
weight: 495
url: /hi/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) विधि

[XmlNode](../../xmlnode/) ऑब्जेक्ट को [XmlReader](../../xmlreader/) में मौजूद जानकारी के आधार पर बनाता है। रीडर को किसी नोड या एट्रीब्यूट पर स्थित होना चाहिए।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | XML स्रोत। |

### वापसी मान

नया [XmlNode](../../xmlnode/) या **nullptr** यदि और नोड नहीं मौजूद हों।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlReader](../../xmlreader/)
* क्लास [XmlDocument](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)