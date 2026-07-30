---
title: RemoveAttribute()
second_title: Aspose.Slides pro referenci API C++
description: Odstraní atribut podle názvu.
type: docs
weight: 235
url: /cs/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) metoda


Odstraní atribut podle názvu.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název atributu, který se má odstranit. Jedná se o kvalifikovaný název. Je porovnáván s **get_Name** hodnotou odpovídajícího uzlu. |

## XmlElement::RemoveAttribute(String, String) metoda


Odstraní atribut se zadaným místním názvem a URI jmenného prostoru. (Pokud odstraněný atribut má výchozí hodnotu, je okamžitě nahrazen.)

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Místní název atributu, který se má odstranit. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu, který se má odstranit. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlElement](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)