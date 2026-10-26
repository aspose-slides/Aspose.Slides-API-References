---
title: ReadToFollowing()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Čte, dokud není nalezen prvek se zadaným kvalifikovaným názvem.
type: docs
weight: 898
url: /cs/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) metoda

Čte, dokud není nalezen prvek se zadaným kvalifikovaným názvem.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název prvku. |

### Návratová hodnota

**true** pokud je nalezen odpovídající prvek; jinak **false** a [XmlReader](../) je ve stavu konce souboru.

## XmlReader::ReadToFollowing(String, String) metoda

Čte, dokud není nalezen prvek se zadaným lokálním názvem a namespace URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název prvku. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru prvku. |

### Návratová hodnota

**true** pokud je nalezen odpovídající prvek; jinak **false** a [XmlReader](../) je ve stavu konce souboru.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)