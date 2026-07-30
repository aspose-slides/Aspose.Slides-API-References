---
title: MoveToAttribute()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přesune se na atribut se zadaným názvem.
type: docs
weight: 456
url: /cs/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) metoda

Přesune se na atribut se zadaným názvem.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Plně kvalifikovaný název atributu. |

### Návratová hodnota

**true** pokud je atribut nalezen; jinak **false**. Pokud **false**, pozice čtečky se nezmění.

## XmlValidatingReader::MoveToAttribute(String, String) metoda

Přesune se na atribut se zadaným lokálním názvem a identifikátorem URI jmenného prostoru.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

**true** pokud je atribut nalezen; jinak **false**. Pokud **false**, pozice čtečky se nezmění.

## XmlValidatingReader::MoveToAttribute(int32_t) metoda

Přesune se na atribut se zadaným indexem.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | **int32_t** | Index atributu. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlValidatingReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)