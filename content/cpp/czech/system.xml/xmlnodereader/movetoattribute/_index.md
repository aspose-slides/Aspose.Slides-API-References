---
title: MoveToAttribute()
second_title: Aspose.Slides pro C++ – reference API
description: Přesune se na atribut se zadaným názvem.
type: docs
weight: 300
url: /cs/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) metoda


Přesune se na atribut se zadaným názvem.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název atributu. |

### Návratová hodnota

**true** pokud je atribut nalezen; jinak **false**. Pokud je **false**, pozice čtečky se nezmění.

## XmlNodeReader::MoveToAttribute(String, String) metoda


Přesune se na atribut se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokální název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

**true** pokud je atribut nalezen; jinak **false**. Pokud je **false**, pozice čtečky se nezmění.

## XmlNodeReader::MoveToAttribute(int32_t) metoda


Přesune se na atribut se zadaným indexem.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| attributeIndex | **int32_t** | Index atributu. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)