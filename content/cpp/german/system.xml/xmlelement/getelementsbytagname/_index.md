---
title: GetElementsByTagName()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt eine XmlNodeList zurück, die eine Liste aller Nachkommen-Elemente enthält, die dem angegebenen XmlElement::get_Name entsprechen."
type: docs
weight: 287
url: /de/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) Methode

Gibt ein [XmlNodeList](../../xmlnodelist/) zurück, das eine Liste aller Nachkommen-Elemente enthält, die dem angegebenen [XmlElement::get_Name](../get_name/) entsprechen.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der Namens-Tag, der übereinstimmen soll. Dies ist ein qualifizierter Name. Er wird mit dem **get_Name**-Wert des übereinstimmenden Knotens verglichen. Das Sternchen (*) ist ein spezieller Wert, der mit allen Tags übereinstimmt. |

### Rückgabewert

Ein [XmlNodeList](../../xmlnodelist/), das eine Liste aller passenden Knoten enthält. Die Liste ist leer, wenn es keine passenden Knoten gibt.

## XmlElement::GetElementsByTagName(String, String) Methode

Gibt ein [XmlNodeList](../../xmlnodelist/) zurück, das eine Liste aller Nachkommen-Elemente enthält, die den angegebenen [XmlElement::get_LocalName](../get_localname/)- und [XmlElement::get_NamespaceURI](../get_namespaceuri/)-Werten entsprechen.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name, der übereinstimmen soll. Das Sternchen (*) ist ein spezieller Wert, der mit allen Tags übereinstimmt. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI, der übereinstimmen soll. |

### Rückgabewert

Ein [XmlNodeList](../../xmlnodelist/), das eine Liste aller passenden Knoten enthält. Die Liste ist leer, wenn es keine passenden Knoten gibt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNodeList](../../xmlnodelist/)
* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)