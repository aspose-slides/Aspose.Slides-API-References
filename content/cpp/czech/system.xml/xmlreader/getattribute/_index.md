---
title: GetAttribute()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Když je v odvozené třídě přepsána, získá hodnotu atributu se zadanou hodnotou XmlReader::get_Name."
type: docs
weight: 599
url: /cs/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) metoda

Když je v odvozené třídě přepsána, získá hodnotu atributu se zadanou hodnotou [XmlReader::get_Name](../get_name/).

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název atributu. |

### Návratová hodnota

Hodnota specifikovaného atributu. Pokud atribut není nalezen nebo je hodnota [String::Empty](../../../system/string/empty/), **nullptr** je vrácena.

## XmlReader::GetAttribute(String, String) metoda

Když je v odvozené třídě přepsána, získá hodnotu atributu se zadanými hodnotami [XmlReader::get_LocalName](../get_localname/) a [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Místní název atributu. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

Hodnota specifikovaného atributu. Pokud atribut není nalezen nebo je hodnota [String::Empty](../../../system/string/empty/), **nullptr** je vrácena. Tato metoda nepřesunuje čtečku.

## XmlReader::GetAttribute(int32_t) metoda

Když je v odvozené třídě přepsána, získá hodnotu atributu se zadaným indexem.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | Index atributu. Index je nulově založený. (První atribut má index 0.) |

### Návratová hodnota

Hodnota specifikovaného atributu. Tato metoda nepřesunuje čtečku.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)