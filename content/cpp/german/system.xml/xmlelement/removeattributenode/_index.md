---
title: RemoveAttributeNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das angegebene XmlAttribute.
type: docs
weight: 274
url: /de/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) Methode

Entfernt das angegebene [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Der [XmlAttribute](../../xmlattribute/) Knoten, der entfernt werden soll. Wenn das entfernte Attribut einen Standardwert hat, wird er sofort ersetzt. |

### Rückgabewert

Das entfernte [XmlAttribute](../../xmlattribute/) oder **nullptr**, wenn **oldAttr** kein Attributknoten des [XmlElement](../) ist.

## XmlElement::RemoveAttributeNode(String, String) Methode

Entfernt das [XmlAttribute](../../xmlattribute/) angegeben durch den lokalen Namen und den Namespace-URI. (Wenn das entfernte Attribut einen Standardwert hat, wird er sofort ersetzt).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des Attributs. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des Attributs. |

### Rückgabewert

Das entfernte [XmlAttribute](../../xmlattribute/) oder **nullptr**, wenn [XmlElement](../) keinen passenden Attributknoten hat.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)