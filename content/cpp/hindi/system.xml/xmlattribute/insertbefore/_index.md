---
title: InsertBefore()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट नोड को निर्दिष्ट रेफरेंस नोड से तुरंत पहले सम्मिलित करता है।
type: docs
weight: 209
url: /hi/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) विधि

निश्चित नोड को निर्दिष्ट रेफरेंस नोड से तुरंत पहले सम्मिलित करता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | इसे सम्मिलित करने के लिए [XmlNode](../../xmlnode/)। |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) जो रेफरेंस नोड है। **newChild** इस नोड के पहले रखा जाता है। |

### रिटर्न मान

डाली गई [XmlNode](../../xmlnode/)।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)