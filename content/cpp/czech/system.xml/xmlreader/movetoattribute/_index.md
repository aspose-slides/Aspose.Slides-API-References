---
title: MoveToAttribute()
second_title: Aspose.Slides pro C++ API reference
description: "Když je v odvozené třídě přepsána, přesune na atribut s určenou hodnotou XmlReader::get_Name."
type: docs
weight: 625
url: /cs/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) metoda

Při přepsání v odvozené třídě přesune na atribut s určenou hodnotou [XmlReader::get_Name](../get_name/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název atributu. |

### Návratová hodnota

**true** pokud je atribut nalezen; jinak **false**. Pokud je **false**, pozice čtečky se nezmění.

## XmlReader::MoveToAttribute(String, String) metoda

Při přepsání v odvozené třídě přesune na atribut s určenými hodnotami [XmlReader::get_LocalName](../get_localname/) a [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Místní název atributu. |
| ns | [String](../../../system/string/) | URI jmenného prostoru atributu. |

### Návratová hodnota

**true** pokud je atribut nalezen; jinak **false**. Pokud je **false**, pozice čtečky se nezmění.

## XmlReader::MoveToAttribute(int32_t) metoda

Při přepsání v odvozené třídě přesune na atribut s určeným indexem.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| i | **int32_t** | Index atributu. |

## Viz také

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)