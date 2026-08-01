---
title: GetElementsByTagName()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een XmlNodeList met een lijst van alle afstammende elementen die overeenkomen met de opgegeven naam.
type: docs
weight: 443
url: /nl/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) methode

Retourneert een [XmlNodeList](../../xmlnodelist/) met een lijst van alle afstammende elementen die overeenkomen met de opgegeven naam.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam om mee te vergelijken. Deze wordt vergeleken met de **get_Name**-waarde van het overeenkomende knooppunt. De speciale waarde **"*"** komt overeen met alle tags. |

### Retourwaarde

Een [XmlNodeList](../../xmlnodelist/) met een lijst van alle overeenkomende knooppunten. Als geen knooppunten overeenkomen met **name**, zal de geretourneerde collectie leeg zijn.

## XmlDocument::GetElementsByTagName(String, String) methode

Retourneert een [XmlNodeList](../../xmlnodelist/) met een lijst van alle afstammende elementen die overeenkomen met de opgegeven [XmlDocument::get_LocalName](../get_localname/) en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De LocalName om mee te vergelijken. De speciale waarde **"*"** komt overeen met alle tags. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI om mee te vergelijken. |

### Retourwaarde

Een [XmlNodeList](../../xmlnodelist/) met een lijst van alle overeenkomende knooppunten. Als geen knooppunten overeenkomen met de opgegeven **localName** en **namespaceURI**, zal de geretourneerde collectie leeg zijn.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNodeList](../../xmlnodelist/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)