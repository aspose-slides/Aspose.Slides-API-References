---
title: ReadToDescendant()
second_title: Aspose.Slides pro C++ API Reference
description: Posune XmlReader na další podřízený prvek se zadaným kvalifikovaným názvem.
type: docs
weight: 911
url: /cs/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) metoda


Posune [XmlReader](../) na další podřízený prvek se zadaným kvalifikovaným názvem.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název prvku, na který se chcete přesunout. |

### Návratová hodnota

**true** pokud byl nalezen odpovídající podřízený prvek; jinak **false**. Pokud není nalezen odpovídající podřazený prvek, [XmlReader](../) je umístěn na koncový tag (hodnota [XmlReader::get_NodeType](../get_nodetype/) je [XmlNodeType::EndElement](../../xmlnodetype/)) prvku. Pokud [XmlReader](../) není umístěn na prvku v okamžiku volání [XmlReader::ReadToDescendant(String)](./), tato metoda vrátí **false** a pozice [XmlReader](../) se nezmění.

## XmlReader::ReadToDescendant(String, String) metoda


Posune [XmlReader](../) na další podřízený prvek se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název prvku, na který se chcete přesunout. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru prvku, na který se chcete přesunout. |

### Návratová hodnota

**true** pokud byl nalezen odpovídající podřízený prvek; jinak **false**. Pokud není nalezen odpovídající podřazený prvek, [XmlReader](../) je umístěn na koncový tag (hodnota [XmlReader::get_NodeType](../get_nodetype/) je [XmlNodeType::EndElement](../../xmlnodetype/)) prvku. Pokud [XmlReader](../) není umístěn na prvku v okamžiku volání [XmlReader::ReadToDescendant(String,String)](./), tato metoda vrátí **false** a pozice [XmlReader](../) se nezmění.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)