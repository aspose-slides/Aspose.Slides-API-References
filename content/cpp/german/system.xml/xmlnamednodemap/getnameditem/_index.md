---
title: GetNamedItem()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft ein XmlNode anhand des Namens ab.
type: docs
weight: 14
url: /de/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) Methode


Ruft ein [XmlNode](../../xmlnode/) anhand des Namens ab.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der qualifizierte Name des abzurufenden Knotens. Er wird mit dem [XmlNode::get_Name](../../xmlnode/get_name/)-Wert des passenden Knotens verglichen. |

### Rückgabewert

Ein [XmlNode](../../xmlnode/) mit dem angegebenen Namen oder **nullptr**, falls kein passender Knoten gefunden wird.

## XmlNamedNodeMap::GetNamedItem(String, String) Methode


Ruft einen Knoten mit den passenden [XmlNode::get_LocalName](../../xmlnode/get_localname/)- und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)-Werten ab.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des abzurufenden Knotens. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-Uniform-Resource-Identifier (URI) des abzurufenden Knotens. |

### Rückgabewert

Ein [XmlNode](../../xmlnode/) mit dem passenden lokalen Namen und dem Namespace-URI oder **nullptr**, falls kein passender Knoten gefunden wird.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNamedNodeMap](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)