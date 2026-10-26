---
title: CreateElement()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří prvek se zadaným názvem.
type: docs
weight: 339
url: /cs/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) metoda

Vytvoří prvek se zadaným názvem.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kvalifikovaný název prvku. Pokud název obsahuje dvojtečku, pak hodnota [XmlNode::get_Prefix](../../xmlnode/get_prefix/) odráží část názvu před dvojtečkou a hodnota [XmlDocument::get_LocalName](../get_localname/) odráží část názvu za dvojtečkou. Kvalifikovaný název nesmí obsahovat předponu **xmlns**. |

### Návratová hodnota

Nový [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) metoda

Vytvoří [XmlElement](../../xmlelement/) s kvalifikovaným názvem a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Kvalifikovaný název prvku. Pokud název obsahuje dvojtečku, pak hodnota [XmlNode::get_Prefix](../../xmlnode/get_prefix/) odráží část názvu před dvojtečkou a hodnota [XmlDocument::get_LocalName](../get_localname/) odráží část názvu za dvojtečkou. Kvalifikovaný název nesmí obsahovat předponu **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | URI jmenného prostoru prvku. |

### Návratová hodnota

Nový [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) metoda

Vytvoří prvek se zadanými [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Předpona nového prvku (pokud existuje). [String::Empty](../../../system/string/empty/) a **nullptr** jsou ekvivalentní. |
| localName | const [String](../../../system/string/)\& | Lokální název nového prvku. |
| namespaceURI | const [String](../../../system/string/)\& | URI jmenného prostoru nového prvku (pokud existuje). [String::Empty](../../../system/string/empty/) a **nullptr** jsou ekvivalentní. |

### Návratová hodnota

Nový [XmlElement](../../xmlelement/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlElement](../../xmlelement/)
* Třída [String](../../../system/string/)
* Třída [XmlDocument](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)