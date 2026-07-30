---
title: SetAttributeNode()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá zadaný XmlAttribute.
type: docs
weight: 261
url: /cs/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) metoda

Přidá zadaný [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Uzlu [XmlAttribute](../../xmlattribute/) k přidání do kolekce atributů pro tento prvek. |

### Návratová hodnota

Pokud atribut nahradí existující atribut se stejným názvem, starý [XmlAttribute](../../xmlattribute/) je vrácen; jinak je vráceno **nullptr**.

## XmlElement::SetAttributeNode(String, String) metoda

Přidá zadaný [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Místní název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

[XmlAttribute](../../xmlattribute/) k přidání.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlAttribute](../../xmlattribute/)
* Třída [XmlElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)