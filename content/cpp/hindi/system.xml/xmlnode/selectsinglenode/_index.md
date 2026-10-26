---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: XPath अभिव्यक्ति से मेल खाने वाले पहले XmlNode का चयन करता है।
type: docs
weight: 352
url: /hi/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) मेथड


पहला [XmlNode](../) चुनता है जो [XPath](../../../system.xml.xpath/) अभिव्यक्ति से मेल खाता है।

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | The [XPath](../../../system.xml.xpath/) अभिव्यक्ति। |

### वापसी मान

पहला [XmlNode](../) जो [XPath](../../../system.xml.xpath/) क्वेरी से मेल खाता है, या **nullptr** यदि कोई मिलते-जुलते नोड न मिले।

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) मेथड


पहला [XmlNode](../) चुनता है जो [XPath](../../../system.xml.xpath/) अभिव्यक्ति से मेल खाता है। [XPath](../../../system.xml.xpath/) अभिव्यक्ति में पाए गए सभी प्रीफ़िक्स प्रदान किए गए [XmlNamespaceManager](../../xmlnamespacemanager/) का उपयोग कर हल किए जाते हैं।

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | The [XPath](../../../system.xml.xpath/) अभिव्यक्ति। |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | एक [XmlNamespaceManager](../../xmlnamespacemanager/) जिसे [XPath](../../../system.xml.xpath/) अभिव्यक्ति में प्रीफ़िक्स के लिए नेमस्पेस हल करने हेतु उपयोग किया जाता है। |

### वापसी मान

पहला [XmlNode](../) जो [XPath](../../../system.xml.xpath/) क्वेरी से मेल खाता है, या **nullptr** यदि कोई मिलते-जुलते नोड न मिले।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)