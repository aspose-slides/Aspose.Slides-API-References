---
title: CreateElement()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een element met de opgegeven naam.
type: docs
weight: 339
url: /nl/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) methode

Maakt een element met de opgegeven naam.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | De gekwalificeerde naam van het element. Als de naam een dubbele punt bevat, dan geeft de [XmlNode::get_Prefix](../../xmlnode/get_prefix/) waarde het deel van de naam vóór de dubbele punt weer en geeft de [XmlDocument::get_LocalName](../get_localname/) waarde het deel van de naam na de dubbele punt weer. De gekwalificeerde naam mag geen prefix **xmlns** bevatten. |

### Retourwaarde

Het nieuwe [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) methode

Maakt een [XmlElement](../../xmlelement/) met de gekwalificeerde naam en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | De gekwalificeerde naam van het element. Als de naam een dubbele punt bevat, dan geeft de [XmlNode::get_Prefix](../../xmlnode/get_prefix/) waarde het deel van de naam vóór de dubbele punt weer en geeft de [XmlDocument::get_LocalName](../get_localname/) waarde het deel van de naam na de dubbele punt weer. De gekwalificeerde naam mag geen prefix **xmlns** bevatten. |
| namespaceURI | const [String](../../../system/string/)\& | De namespace-URI van het element. |

### Retourwaarde

Het nieuwe [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) methode

Maakt een element met de opgegeven [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | De prefix van het nieuwe element (indien aanwezig). [String::Empty](../../../system/string/empty/) en **nullptr** zijn equivalent. |
| localName | const [String](../../../system/string/)\& | De lokale naam van het nieuwe element. |
| namespaceURI | const [String](../../../system/string/)\& | De namespace-URI van het nieuwe element (indien aanwezig). [String::Empty](../../../system/string/empty/) en **nullptr** zijn equivalent. |

### Retourwaarde

Het nieuwe [XmlElement](../../xmlelement/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlElement](../../xmlelement/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)