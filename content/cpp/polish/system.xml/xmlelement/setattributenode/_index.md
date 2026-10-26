---
title: SetAttributeNode()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Dodaje określony XmlAttribute.
type: docs
weight: 261
url: /pl/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) metoda

Dodaje określony [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Węzeł [XmlAttribute](../../xmlattribute/) do dodania do kolekcji atrybutów tego elementu. |

### Wartość zwracana

Jeśli atrybut zastępuje istniejący atrybut o tej samej nazwie, zwracany jest stary [XmlAttribute](../../xmlattribute/); w przeciwnym razie zwracane jest **nullptr**.

## XmlElement::SetAttributeNode(String, String) metoda

Dodaje określony [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu. |

### Wartość zwracana

[XmlAttribute](../../xmlattribute/) do dodania.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)