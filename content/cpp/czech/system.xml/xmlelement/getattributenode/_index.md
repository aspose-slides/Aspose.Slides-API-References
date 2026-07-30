---
title: GetAttributeNode()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací XmlAttribute se zadaným názvem.
type: docs
weight: 248
url: /cs/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) metoda


Vrací [XmlAttribute](../../xmlattribute/) se zadaným názvem.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název atributu k načtení. Jedná se o kvalifikovaný název. Je porovnán s hodnotou **get_Name** odpovídajícího uzlu. |

### Návratová hodnota

Zadaný [XmlAttribute](../../xmlattribute/) nebo **nullptr**, pokud nebyl nalezen odpovídající atribut.

## XmlElement::GetAttributeNode(String, String) metoda


Vrací [XmlAttribute](../../xmlattribute/) se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

Zadaný [XmlAttribute](../../xmlattribute/) nebo **nullptr**, pokud nebyl nalezen odpovídající atribut.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlAttribute](../../xmlattribute/)
* Třída [String](../../../system/string/)
* Třída [XmlElement](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)