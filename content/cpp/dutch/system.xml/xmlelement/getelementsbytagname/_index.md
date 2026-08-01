---
title: GetElementsByTagName()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert een XmlNodeList die een lijst bevat van alle afstammende elementen die overeenkomen met de opgegeven XmlElement::get_Name."
type: docs
weight: 287
url: /nl/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) methode

Retourneert een [XmlNodeList](../../xmlnodelist/) die een lijst bevat van alle afstammende elementen die overeenkomen met de opgegeven [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De naam-tag om te vergelijken. Dit is een gekwalificeerde naam. Het wordt vergeleken met de **get_Name**-waarde van het overeenkomende knooppunt. Het sterretje (*) is een speciale waarde die alle tags overeenkomt. |

### Retourwaarde

Een [XmlNodeList](../../xmlnodelist/) die een lijst bevat van alle overeenkomende knooppunten. De lijst is leeg als er geen overeenkomende knooppunten zijn.

## XmlElement::GetElementsByTagName(String, String) methode

Retourneert een [XmlNodeList](../../xmlnodelist/) die een lijst bevat van alle afstammende elementen die overeenkomen met de opgegeven [XmlElement::get_LocalName](../get_localname/) en [XmlElement::get_NamespaceURI](../get_namespaceuri/) waarden.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam om te vergelijken. Het sterretje (*) is een speciale waarde die alle tags overeenkomt. |
| namespaceURI | [String](../../../system/string/) | De naamruimte-URI om te vergelijken. |

### Retourwaarde

Een [XmlNodeList](../../xmlnodelist/) die een lijst bevat van alle overeenkomende knooppunten. De lijst is leeg als er geen overeenkomende knooppunten zijn.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNodeList](../../xmlnodelist/)
* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)