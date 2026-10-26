---
title: GetElementsByTagName()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक XmlNodeList लौटाता है जिसमें सभी उत्तराधिकारियों तत्वों की सूची होती है जो निर्दिष्ट नाम से मेल खाते हैं।
type: docs
weight: 443
url: /hi/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) मेथड


एक [XmlNodeList](../../xmlnodelist/) लौटाता है जिसमें सभी उतराधिकारियों तत्वों की सूची होती है जो निर्दिष्ट नाम से मेल खाते हैं।

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | मैच करने के लिए योग्य नाम। यह मिलते हुए नोड के **get_Name** मान से मेल खाता है। विशेष मान **"*"** सभी टैग्स से मेल खाता है। |

### रिटर्न मान

एक [XmlNodeList](../../xmlnodelist/) जिसमें सभी मेल खाने वाले नोड्स की सूची होती है। अगर कोई नोड **name** से मेल नहीं खाता, तो लौटाई गई कलेक्शन खाली होगी।

## XmlDocument::GetElementsByTagName(String, String) मेथड


एक [XmlNodeList](../../xmlnodelist/) लौटाता है जिसमें सभी उतराधिकारियों तत्वों की सूची होती है जो निर्दिष्ट [XmlDocument::get_LocalName](../get_localname/) और [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) से मेल खाते हैं।

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | मैच करने के लिए LocalName। विशेष मान **"*"** सभी टैग्स से मेल खाता है। |
| namespaceURI | [String](../../../system/string/) | मैच करने के लिए NamespaceURI। |

### रिटर्न मान

एक [XmlNodeList](../../xmlnodelist/) जिसमें सभी मेल खाने वाले नोड्स की सूची होती है। अगर कोई नोड निर्दिष्ट **localName** और **namespaceURI** से मेल नहीं खाता, तो लौटाई गई कलेक्शन खाली होगी।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNodeList](../../xmlnodelist/)
* क्लास [String](../../../system/string/)
* क्लास [XmlDocument](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)