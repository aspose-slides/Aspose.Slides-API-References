---
title: GetAttributeNode()
second_title: Aspose.Slides dla C++ API Referencja
description: Zwraca XmlAttribute o określonej nazwie.
type: docs
weight: 248
url: /pl/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) metoda


Zwraca [XmlAttribute](../../xmlattribute/) o określonej nazwie.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa atrybutu do pobrania. Jest to nazwa kwalifikowana. Jest dopasowywana do wartości **get_Name** dopasowanego węzła. |

### Wartość zwracana

Określony [XmlAttribute](../../xmlattribute/) lub **nullptr**, jeśli nie znaleziono pasującego atrybutu.

## XmlElement::GetAttributeNode(String, String) metoda


Zwraca [XmlAttribute](../../xmlattribute/) o określonej nazwie lokalnej i URI przestrzeni nazw.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Określony [XmlAttribute](../../xmlattribute/) lub **nullptr**, jeśli nie znaleziono pasującego atrybutu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlAttribute](../../xmlattribute/)
* Klasa [String](../../../system/string/)
* Klasa [XmlElement](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)