---
title: CreateElement()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein Element mit dem angegebenen Namen.
type: docs
weight: 339
url: /de/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) Methode

Erstellt ein Element mit dem angegebenen Namen.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Der qualifizierte Name des Elements. Enthält der Name einen Doppelpunkt, dann gibt der [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-Wert den Teil des Namens vor dem Doppelpunkt und der [XmlDocument::get_LocalName](../get_localname/)-Wert den Teil des Namens nach dem Doppelpunkt wieder. Der qualifizierte Name darf kein Präfix **xmlns** enthalten. |

### Rückgabewert

Das neue [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) Methode

Erstellt ein [XmlElement](../../xmlelement/) mit dem qualifizierten Namen und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Der qualifizierte Name des Elements. Enthält der Name einen Doppelpunkt, dann gibt der [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-Wert den Teil des Namens vor dem Doppelpunkt und der [XmlDocument::get_LocalName](../get_localname/)-Wert den Teil des Namens nach dem Doppelpunkt wieder. Der qualifizierte Name darf kein Präfix **xmlns** enthalten. |
| namespaceURI | const [String](../../../system/string/)\& | Der Namespace-URI des Elements. |

### Rückgabewert

Das neue [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) Methode

Erstellt ein Element mit den angegebenen [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Das Präfix des neuen Elements (falls vorhanden). [String::Empty](../../../system/string/empty/) und **nullptr** sind äquivalent. |
| localName | const [String](../../../system/string/)\& | Der lokale Name des neuen Elements. |
| namespaceURI | const [String](../../../system/string/)\& | Der Namespace-URI des neuen Elements (falls vorhanden). [String::Empty](../../../system/string/empty/) und **nullptr** sind äquivalent. |

### Rückgabewert

Das neue [XmlElement](../../xmlelement/).

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlElement](../../xmlelement/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)