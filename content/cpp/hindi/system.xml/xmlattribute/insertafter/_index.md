---
title: InsertAfter()
second_title: C++ के लिये Aspose.Slides API संदर्भ
description: निर्दिष्ट रेफ़रेंस नोड के तुरंत बाद निर्दिष्ट नोड को सम्मिलित करता है।
type: docs
weight: 222
url: /hi/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) मेथड

निर्दिष्ट नोड को निर्दिष्ट रेफ़रेंस नोड के तुरंत बाद सम्मिलित करता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) को सम्मिलित करने के लिए। |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) जो रेफ़रेंस नोड है। **newChild** को **refChild** के बाद रखा जाता है। |

### रिटर्न वैल्यू

[XmlNode](../../xmlnode/) को सम्मिलित किया गया।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)