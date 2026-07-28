---
title: CreateElement()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy elemet a megadott névvel.
type: docs
weight: 339
url: /hu/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) metódus


Létrehoz egy elemet a megadott névvel.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Az elem kvalifikált neve. Ha a név kettőspontot tartalmaz, akkor a [XmlNode::get_Prefix](../../xmlnode/get_prefix/) érték a kettőspont előtti részt, a [XmlDocument::get_LocalName](../get_localname/) érték pedig a kettőspont utáni részt tükrözi. A kvalifikált név nem tartalmazhat **xmlns** előtagot. |

### Visszatérési érték

Az új [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) metódus


Létrehoz egy [XmlElement](../../xmlelement/) a kvalifikált névvel és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) értékkel.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Az elem kvalifikált neve. Ha a név kettőspontot tartalmaz, akkor a [XmlNode::get_Prefix](../../xmlnode/get_prefix/) érték a kettőspont előtti részt, a [XmlDocument::get_LocalName](../get_localname/) érték pedig a kettőspont utáni részt tükrözi. A kvalifikált név nem tartalmazhat **xmlns** előtagot. |
| namespaceURI | const [String](../../../system/string/)\& | Az elem névtér-URI-ja. |

### Visszatérési érték

Az új [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) metódus


Létrehoz egy elemet a megadott [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) értékekkel.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Az új elem előtagja (ha van). [String::Empty](../../../system/string/empty/) és **nullptr** egyenértékű. |
| localName | const [String](../../../system/string/)\& | Az új elem helyi neve. |
| namespaceURI | const [String](../../../system/string/)\& | Az új elem névtér-URI-ja (ha van). [String::Empty](../../../system/string/empty/) és **nullptr** egyenértékű. |

### Visszatérési érték

Az új [XmlElement](../../xmlelement/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlElement](../../xmlelement/)
* Osztály [String](../../../system/string/)
* Osztály [XmlDocument](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)