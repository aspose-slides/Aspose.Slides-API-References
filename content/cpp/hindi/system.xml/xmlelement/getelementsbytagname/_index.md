---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API संदर्भ
description: "निर्दिष्ट XmlElement::get_Name से मेल खाने वाले सभी उत्तराधिकारियों के तत्वों की सूची वाले XmlNodeList को लौटाता है।"
type: docs
weight: 287
url: /hi/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) मेथड


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | मैच करने के लिए name टैग। यह एक qualified name है। इसे मिलान नोड के **get_Name** मान के विरुद्ध मिलाया जाता है। एस्टेरिस्क (*) एक विशेष मान है जो सभी टैग्स से मेल खाता है। |

### वापसी मान

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. The list is empty if there are no matching nodes.

## XmlElement::GetElementsByTagName(String, String) मेथड


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlElement::get_LocalName](../get_localname/) and [XmlElement::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | मैच करने के लिए स्थानीय नाम। एस्टेरिस्क (*) एक विशेष मान है जो सभी टैग्स से मेल खाता है। |
| namespaceURI | [String](../../../system/string/) | मैच करने के लिए नेमस्पेस URI। |

### वापसी मान

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. The list is empty if there are no matching nodes.

## भी देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)