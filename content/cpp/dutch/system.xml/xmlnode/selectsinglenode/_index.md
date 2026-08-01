---
title: SelectSingleNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Selecteert de eerste XmlNode die overeenkomt met de XPath-expressie.
type: docs
weight: 352
url: /nl/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) methode


Selecteert het eerste [XmlNode](../) dat overeenkomt met de [XPath](../../../system.xml.xpath/) expressie.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | De [XPath](../../../system.xml.xpath/) expressie. |

### Retourwaarde

Het eerste [XmlNode](../) dat overeenkomt met de [XPath](../../../system.xml.xpath/) query of **nullptr** als er geen overeenkomende knoop wordt gevonden.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) methode


Selecteert het eerste [XmlNode](../) dat overeenkomt met de [XPath](../../../system.xml.xpath/) expressie. Eventuele prefixes die worden gevonden in de [XPath](../../../system.xml.xpath/) expressie worden opgelost met behulp van de meegeleverde [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | De [XPath](../../../system.xml.xpath/) expressie. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Een [XmlNamespaceManager](../../xmlnamespacemanager/) om te gebruiken voor het oplossen van namespaces voor prefixes in de [XPath](../../../system.xml.xpath/) expressie. |

### Retourwaarde

Het eerste [XmlNode](../) dat overeenkomt met de [XPath](../../../system.xml.xpath/) query of **nullptr** als er geen overeenkomende knoop wordt gevonden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlNamespaceManager](../../xmlnamespacemanager/)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)