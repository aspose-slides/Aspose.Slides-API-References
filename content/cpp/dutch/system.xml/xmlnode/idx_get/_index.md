---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert het eerste kindelement met de opgegeven XmlNode::get_Name."
type: docs
weight: 586
url: /nl/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) methode


Retourneert het eerste kindelement met de opgegeven [XmlNode::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het element om op te halen. |

### Retourwaarde

Het eerste [XmlElement](../../xmlelement/) dat overeenkomt met de opgegeven naam. Het retourneert **nullptr** als er geen overeenkomst is.

## XmlNode::idx_get(String, String) methode


Retourneert het eerste kindelement met de opgegeven [XmlNode::get_LocalName](../get_localname/) en [XmlNode::get_NamespaceURI](../get_namespaceuri/) waarden.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | De lokale naam van het element. |
| ns | [String](../../../system/string/) | De namespace-URI van het element. |

### Retourwaarde

Het eerste [XmlElement](../../xmlelement/) met de overeenkomende **localname** en **ns**. Het retourneert **nullptr** als er geen overeenkomst is.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlElement](../../xmlelement/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)