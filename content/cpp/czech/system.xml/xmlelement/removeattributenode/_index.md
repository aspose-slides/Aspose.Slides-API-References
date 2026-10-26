---
title: RemoveAttributeNode()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje určený XmlAttribute.
type: docs
weight: 274
url: /cs/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) metoda


Odstraňuje určený [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Uzlu [XmlAttribute](../../xmlattribute/) k odstranění. Pokud má odebraný atribut výchozí hodnotu, je ihned nahrazena. |

### Návratová hodnota

Odstraněný [XmlAttribute](../../xmlattribute/) nebo **nullptr**, pokud **oldAttr** není atributovým uzlem [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) metoda


Odstraňuje [XmlAttribute](../../xmlattribute/) určený místním názvem a URI jmenného prostoru. (Pokud má odebraný atribut výchozí hodnotu, je ihned nahrazena).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Místní název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

Odstraněný [XmlAttribute](../../xmlattribute/) nebo **nullptr**, pokud [XmlElement](../) nemá odpovídající uzel atributu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlAttribute](../../xmlattribute/)
* Třída [XmlElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)