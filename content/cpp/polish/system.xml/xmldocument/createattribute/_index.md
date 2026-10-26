---
title: CreateAttribute()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy XmlAttribute o podanej nazwie.
type: docs
weight: 274
url: /pl/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) metoda


Tworzy [XmlAttribute](../../xmlattribute/) o podanej nazwie.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | W pełni kwalifikowana nazwa atrybutu. Jeśli nazwa zawiera dwukropek, wartość [XmlNode::get_Prefix](../../xmlnode/get_prefix/) odzwierciedla część nazwy poprzedzającą pierwszy dwukropek, a wartość [XmlDocument::get_LocalName](../get_localname/) odzwierciedla część nazwy po pierwszym dwukropku. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) pozostaje pusty, chyba że prefiks jest rozpoznawanym wbudowanym prefiksem, takim jak **xmlns**. W takim przypadku get_NamespaceURI ma wartość [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Wartość zwracana

Nowy [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) metoda


Tworzy [XmlAttribute](../../xmlattribute/) o podanej w pełni kwalifikowanej nazwie i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | W pełni kwalifikowana nazwa atrybutu. Jeśli nazwa zawiera dwukropek, wartość [XmlNode::get_Prefix](../../xmlnode/get_prefix/) odzwierciedla część nazwy poprzedzającą dwukropek, a wartość [XmlDocument::get_LocalName](../get_localname/) odzwierciedla część nazwy po dwukropku. |
| namespaceURI | const [String](../../../system/string/)\& | NamespaceURI atrybutu. Jeżeli w pełni kwalifikowana nazwa zawiera prefiks **xmlns**, ten parametr musi mieć wartość [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Wartość zwracana

Nowy [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) metoda


Tworzy [XmlAttribute](../../xmlattribute/) o podanych [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks atrybutu (jeśli istnieje). [String::Empty](../../../system/string/empty/) i **nullptr** są równoważne. |
| localName | const [String](../../../system/string/)\& | Lokalna nazwa atrybutu. |
| namespaceURI | const [String](../../../system/string/)\& | Namespace URI atrybutu (jeśli istnieje). [String::Empty](../../../system/string/empty/) i **nullptr** są równoważne. Jeśli **prefix** jest **xmlns**, ten parametr musi mieć wartość [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;), w przeciwnym razie zostanie zgłoszony wyjątek. |

### Wartość zwracana

Nowy [XmlAttribute](../../xmlattribute/).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlAttribute](../../xmlattribute/)
* Klasa [String](../../../system/string/)
* Klasa [XmlDocument](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)