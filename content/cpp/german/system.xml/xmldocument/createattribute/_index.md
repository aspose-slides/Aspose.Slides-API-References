---
title: CreateAttribute()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein XmlAttribute mit dem angegebenen Namen.
type: docs
weight: 274
url: /de/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) Methode

Erstellt ein [XmlAttribute](../../xmlattribute/) mit dem angegebenen Namen.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Der qualifizierte Name des Attributs. Falls der Name einen Doppelpunkt enthält, gibt der [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-Wert den Teil des Namens vor dem ersten Doppelpunkt wieder und der [XmlDocument::get_LocalName](../get_localname/)-Wert den Teil des Namens nach dem ersten Doppelpunkt. Der [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) bleibt leer, es sei denn, das Präfix ist ein anerkanntes eingebautes Präfix wie **xmlns**. In diesem Fall hat get_NamespaceURI den Wert [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Rückgabewert

Das neue [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) Methode

Erstellt ein [XmlAttribute](../../xmlattribute/) mit dem angegebenen qualifizierten Namen und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Der qualifizierte Name des Attributs. Falls der Name einen Doppelpunkt enthält, gibt der [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-Wert den Teil des Namens vor dem Doppelpunkt wieder und der [XmlDocument::get_LocalName](../get_localname/)-Wert den Teil des Namens nach dem Doppelpunkt. |
| namespaceURI | const [String](../../../system/string/)\& | Der namespaceURI des Attributs. Falls der qualifizierte Name ein Präfix **xmlns** enthält, muss dieser Parameter [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) sein. |

### Rückgabewert

Das neue [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) Methode

Erstellt ein [XmlAttribute](../../xmlattribute/) mit den angegebenen [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Das Präfix des Attributs (falls vorhanden). [String::Empty](../../../system/string/empty/) und **nullptr** sind äquivalent. |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Attributs. |
| namespaceURI | const [String](../../../system/string/)\& | Der namespace URI des Attributs (falls vorhanden). [String::Empty](../../../system/string/empty/) und **nullptr** sind äquivalent. Wenn **prefix** **xmlns** ist, muss dieser Parameter [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) sein, sonst wird eine Ausnahme ausgelöst. |

### Rückgabewert

Das neue [XmlAttribute](../../xmlattribute/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)