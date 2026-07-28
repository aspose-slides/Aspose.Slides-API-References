---
title: RemoveAttributeNode()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Usuwa określony XmlAttribute.
type: docs
weight: 274
url: /pl/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) metoda

Usuwa określony [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Węzeł [XmlAttribute](../../xmlattribute/) do usunięcia. Jeśli usunięty atrybut ma wartość domyślną, zostaje ona natychmiast zastąpiona. |

### Wartość zwracana

Usunięty [XmlAttribute](../../xmlattribute/) lub **nullptr**, jeśli **oldAttr** nie jest węzłem atrybutu [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) metoda

Usuwa [XmlAttribute](../../xmlattribute/) określony przez nazwę lokalną i identyfikator URI przestrzeni nazw. (Jeśli usunięty atrybut ma wartość domyślną, zostaje ona natychmiast zastąpiona).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Usunięty [XmlAttribute](../../xmlattribute/) lub **nullptr**, jeśli [XmlElement](../) nie ma pasującego węzła atrybutu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlAttribute](../../xmlattribute/)
* Klasa [XmlElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)