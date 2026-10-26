---
title: CreateAttribute()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří XmlAttribute se zadaným názvem.
type: docs
weight: 274
url: /cs/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method

Vytvoří [XmlAttribute](../../xmlattribute/) se zadaným názvem.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kvalifikovaný název atributu. Pokud název obsahuje dvojtečku, hodnota [XmlNode::get_Prefix](../../xmlnode/get_prefix/) odráží část názvu před první dvojtečkou a hodnota [XmlDocument::get_LocalName](../get_localname/) odráží část názvu za první dvojtečkou. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) zůstává prázdná, pokud není předpona rozpoznanou vestavěnou předponou, jako je **xmlns**. V tomto případě má get_NamespaceURI hodnotu [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Návratová hodnota

Nový [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) method

Vytvoří [XmlAttribute](../../xmlattribute/) se zadaným kvalifikovaným názvem a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Kvalifikovaný název atributu. Pokud název obsahuje dvojtečku, hodnota [XmlNode::get_Prefix](../../xmlnode/get_prefix/) odráží část názvu před dvojtečkou a hodnota [XmlDocument::get_LocalName](../get_localname/) odráží část názvu za dvojtečkou. |
| namespaceURI | const [String](../../../system/string/)\& | NamespaceURI atributu. Pokud kvalifikovaný název obsahuje předponu **xmlns**, pak tento parametr musí být [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Návratová hodnota

Nový [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method

Vytvoří [XmlAttribute](../../xmlattribute/) se zadaným [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Předpona atributu (pokud existuje). [String::Empty](../../../system/string/empty/) a **nullptr** jsou ekvivalentní. |
| localName | const [String](../../../system/string/)\& | Lokální název atributu. |
| namespaceURI | const [String](../../../system/string/)\& | Namespace URI atributu (pokud existuje). [String::Empty](../../../system/string/empty/) a **nullptr** jsou ekvivalentní. Pokud je **prefix** **xmlns**, pak tento parametr musí být [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;), jinak je vyvolána výjimka. |

### Návratová hodnota

Nový [XmlAttribute](../../xmlattribute/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlAttribute](../../xmlattribute/)
* Třída [String](../../../system/string/)
* Třída [XmlDocument](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)