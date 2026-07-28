---
title: CreateElement()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy element o określonej nazwie.
type: docs
weight: 339
url: /pl/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) metoda

Tworzy element o określonej nazwie.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kwalifikowana nazwa elementu. Jeśli nazwa zawiera dwukropek, to wartość [XmlNode::get_Prefix](../../xmlnode/get_prefix/) odzwierciedla część nazwy przed dwukropkiem, a wartość [XmlDocument::get_LocalName](../get_localname/) odzwierciedla część po dwukropku. Kwalifikowana nazwa nie może zawierać prefiksu **xmlns**. |

### Wartość zwracana

Nowy [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) metoda

Tworzy [XmlElement](../../xmlelement/) z kwalifikowaną nazwą oraz [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Kwalifikowana nazwa elementu. Jeśli nazwa zawiera dwukropek, to wartość [XmlNode::get_Prefix](../../xmlnode/get_prefix/) odzwierciedla część nazwy przed dwukropkiem, a wartość [XmlDocument::get_LocalName](../get_localname/) odzwierciedla część po dwukropku. Kwalifikowana nazwa nie może zawierać prefiksu **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | URI przestrzeni nazw elementu. |

### Wartość zwracana

Nowy [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) metoda

Tworzy element o określonych [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks nowego elementu (jeśli istnieje). [String::Empty](../../../system/string/empty/) i **nullptr** są równoważne. |
| localName | const [String](../../../system/string/)\& | Lokalna nazwa nowego elementu. |
| namespaceURI | const [String](../../../system/string/)\& | URI przestrzeni nazw nowego elementu (jeśli istnieje). [String::Empty](../../../system/string/empty/) i **nullptr** są równoważne. |

### Wartość zwracana

Nowy [XmlElement](../../xmlelement/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlElement](../../xmlelement/)
* Klasa [String](../../../system/string/)
* Klasa [XmlDocument](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)