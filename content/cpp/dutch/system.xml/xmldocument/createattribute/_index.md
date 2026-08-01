---
title: CreateAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een XmlAttribute met de opgegeven naam.
type: docs
weight: 274
url: /nl/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) methode

Maakt een [XmlAttribute](../../xmlattribute/) met de opgegeven naam.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | De gekwalificeerde naam van het attribuut. Als de naam een dubbele punt bevat, geeft de [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-waarde het deel van de naam weer dat vóór de eerste dubbele punt staat en geeft de [XmlDocument::get_LocalName](../get_localname/)-waarde het deel van de naam weer dat na de eerste dubbele punt volgt. De [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) blijft leeg tenzij het voorvoegsel een herkende ingebouwde prefix is, zoals **xmlns**. In dit geval heeft get_NamespaceURI een waarde van [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Retourwaarde

De nieuwe [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) methode

Maakt een [XmlAttribute](../../xmlattribute/) met de opgegeven gekwalificeerde naam en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | De gekwalificeerde naam van het attribuut. Als de naam een dubbele punt bevat, geeft de [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-waarde het deel van de naam weer dat vóór de dubbele punt staat en geeft de [XmlDocument::get_LocalName](../get_localname/)-waarde het deel van de naam weer dat na de dubbele punt volgt. |
| namespaceURI | const [String](../../../system/string/)\& | De namespaceURI van het attribuut. Als de gekwalificeerde naam een prefix **xmlns** bevat, moet deze parameter [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) zijn. |

### Retourwaarde

De nieuwe [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) methode

Maakt een [XmlAttribute](../../xmlattribute/) met de opgegeven [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Het prefix van het attribuut (indien aanwezig). [String::Empty](../../../system/string/empty/) en **nullptr** zijn equivalent. |
| localName | const [String](../../../system/string/)\& | De lokale naam van het attribuut. |
| namespaceURI | const [String](../../../system/string/)\& | De namespace-URI van het attribuut (indien aanwezig). [String::Empty](../../../system/string/empty/) en **nullptr** zijn equivalent. Als **prefix** **xmlns** is, moet deze parameter [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) zijn, anders wordt er een uitzondering gegooid. |

### Retourwaarde

De nieuwe [XmlAttribute](../../xmlattribute/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)