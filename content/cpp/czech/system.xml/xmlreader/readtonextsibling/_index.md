---
title: ReadToNextSibling()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Posune XmlReader na další sourozenecký prvek se zadaným kvalifikovaným názvem.
type: docs
weight: 924
url: /cs/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) metoda


Posune [XmlReader](../) na další sourozenecký prvek se zadaným kvalifikovaným názvem.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název sourozeneckého prvku, na který se chcete přesunout. |

### Návratová hodnota

**true** pokud je nalezen odpovídající sourozenecký prvek; jinak **false**. Pokud není nalezen odpovídající sourozenecký prvek, [XmlReader](../) je umístěn na koncový tag ([XmlReader::get_NodeType](../get_nodetype/) hodnota je [XmlNodeType::EndElement](../../xmlnodetype/)) nadřazeného prvku.

## XmlReader::ReadToNextSibling(String, String) metoda


Posune [XmlReader](../) na další sourozenecký prvek se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název sourozeneckého prvku, na který se chcete přesunout. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru sourozeneckého prvku, na který se chcete přesunout. |

### Návratová hodnota

**true** pokud je nalezen odpovídající sourozenecký prvek; jinak **false**. Pokud není nalezen odpovídající sourozenecký prvek, [XmlReader](../) je umístěn na koncový tag ([XmlReader::get_NodeType](../get_nodetype/) hodnota je [XmlNodeType::EndElement](../../xmlnodetype/)) nadřazeného prvku.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)