---
title: CreateAttribute()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy XmlAttribute elemet a megadott névvel.
type: docs
weight: 274
url: /hu/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) módszer

Létrehoz egy [XmlAttribute](../../xmlattribute/) a megadott névvel.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Az attribútum minősített neve. Ha a név kettőspontot tartalmaz, a [XmlNode::get_Prefix](../../xmlnode/get_prefix/) érték a első kettőpont előtt álló részt tükrözi, a [XmlDocument::get_LocalName](../get_localname/) érték pedig az első kettőpont után álló részt tükrözi. A [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) üres marad, kivéve ha az előtag egy ismert beépített előtag, például **xmlns**. Ebben az esetben a get_NamespaceURI értéke [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Visszatérési érték

Az új [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) módszer

Létrehoz egy [XmlAttribute](../../xmlattribute/) a megadott minősített névvel és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Az attribútum minősített neve. Ha a név kettő pontot tartalmaz, akkor a [XmlNode::get_Prefix](../../xmlnode/get_prefix/) érték a kettőpont előtt álló részt tükrözi, a [XmlDocument::get_LocalName](../get_localname/) érték pedig a kettőpont után álló részt tükrözi. |
| namespaceURI | const [String](../../../system/string/)\& | Az attribútum namespaceURI-je. Ha a minősített név **xmlns** előtagot tartalmaz, akkor ennek a paraméternek [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) kell lennie. |

### Visszatérési érték

Az új [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) módszer

Létrehoz egy [XmlAttribute](../../xmlattribute/) a megadott [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Az attribútum előtagja (ha van). [String::Empty](../../../system/string/empty/) és **nullptr** ekvivalens. |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve. |
| namespaceURI | const [String](../../../system/string/)\& | Az attribútum névtér-URI-ja (ha van). [String::Empty](../../../system/string/empty/) és **nullptr** ekvivalens. Ha **prefix** **xmlns**, akkor ennek a paraméternek [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) kell lennie, ellenkező esetben kivétel kerül dobásra. |

### Visszatérési érték

Az új [XmlAttribute](../../xmlattribute/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlAttribute](../../xmlattribute/)
* Osztály [String](../../../system/string/)
* Osztály [XmlDocument](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)