---
title: SelectNodes()
second_title: Aspose.Slides for C++ API संदर्भ
description: XPath अभिव्यक्ति से मेल खाने वाले नोड्स की सूची का चयन करता है।
type: docs
weight: 365
url: /hi/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) मेथड

[XPath](../../../system.xml.xpath/) अभिव्यक्ति से मेल खाने वाले नोड्स की सूची का चयन करता है।

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) अभिव्यक्ति। |

### रिटर्न मान

[XmlNodeList](../../xmlnodelist/) जिसमें [XPath](../../../system.xml.xpath/) क्वेरी से मेल खाने वाले नोड्स का संग्रह होता है।

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) मेथड

[XPath](../../../system.xml.xpath/) अभिव्यक्ति से मेल खाने वाले नोड्स की सूची का चयन करता है। [XPath](../../../system.xml.xpath/) अभिव्यक्ति में पाए गए कोई भी उपसर्ग प्रदान किए गए [XmlNamespaceManager](../../xmlnamespacemanager/) का उपयोग करके हल किए जाते हैं।

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) अभिव्यक्ति। |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XPath](../../../system.xml.xpath/) अभिव्यक्ति में उपसर्गों के नेमस्पेस को हल करने के लिए उपयोग किया गया एक [XmlNamespaceManager](../../xmlnamespacemanager/)। |

### रिटर्न मान

[XmlNodeList](../../xmlnodelist/) जिसमें [XPath](../../../system.xml.xpath/) क्वेरी से मेल खाने वाले नोड्स का संग्रह होता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)