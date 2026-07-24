---
title: RemoveNamedItem()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt den Knoten aus dem XmlNamedNodeMap.
type: docs
weight: 40
url: /de/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) Methode

Entfernt den Knoten aus dem [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des zu entfernenden Knotens. Der Name wird mit dem [XmlNode::get_Name](../../xmlnode/get_name/)-Wert des passenden Knotens abgeglichen. |

### Rückgabewert

Der [XmlNode](../../xmlnode/) wurde aus diesem [XmlNamedNodeMap](../) entfernt oder **nullptr**, wenn kein passender Knoten gefunden wurde.

## XmlNamedNodeMap::RemoveNamedItem(String, String) Methode

Entfernt einen Knoten mit den übereinstimmenden [XmlNode::get_LocalName](../../xmlnode/get_localname/)- und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)-Werten.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des zu entfernenden Knotens. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des zu entfernenden Knotens. |

### Rückgabewert

Der [XmlNode](../../xmlnode/) wurde entfernt oder **nullptr**, wenn kein passender Knoten gefunden wurde.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNamedNodeMap](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)