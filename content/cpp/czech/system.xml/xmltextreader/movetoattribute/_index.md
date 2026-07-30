---
title: MoveToAttribute()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přesune se na atribut se zadaným názvem.
type: docs
weight: 508
url: /cs/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) metoda


Přesune se na atribut se zadaným názvem.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Plně kvalifikovaný název atributu. |

### Návratová hodnota

**true** pokud je atribut nalezen; jinak **false**. Pokud **false**, pozice čtečky se nemění.

## XmlTextReader::MoveToAttribute(String, String) metoda


Přesune se na atribut se zadaným místním názvem a URI jmenného prostoru.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Místní název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

**true** pokud je atribut nalezen; jinak **false**. Pokud **false**, pozice čtečky se nemění.

## XmlTextReader::MoveToAttribute(int32_t) metoda


Přesune se na atribut se zadaným indexem.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | **int32_t** | Index atributu. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)