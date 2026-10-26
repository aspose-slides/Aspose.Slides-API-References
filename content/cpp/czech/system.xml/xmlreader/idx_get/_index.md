---
title: idx_get()
second_title: Aspose.Slides pro C++ – referenční API
description: Když je přepsána v odvozené třídě, získá hodnotu atributu se zadaným indexem.
type: docs
weight: 612
url: /cs/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) metoda

Když je přepsána v odvozené třídě, získá hodnotu atributu se zadaným indexem.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | **int32_t** | Index atributu. |

### Návratová hodnota

Hodnota zadaného atributu.

## XmlReader::idx_get(String) metoda

Když je přepsána v odvozené třídě, získá hodnotu atributu se zadanou hodnotou [XmlReader::get_Name](../get_name/).

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název atributu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud atribut není nalezen, vrací se **nullptr**.

## XmlReader::idx_get(String, String) metoda

Když je přepsána v odvozené třídě, získá hodnotu atributu se zadanými hodnotami [XmlReader::get_LocalName](../get_localname/) a [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Místní název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

Hodnota zadaného atributu. Pokud atribut není nalezen, vrací se **nullptr**.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)