---
title: ReadToFollowing()
second_title: Aspose.Slides C++ API referencia
description: Addig olvas, amíg a megadott minősített névvel rendelkező elem nem található.
type: docs
weight: 898
url: /hu/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) metódus

Olvas addig, amíg a megadott minősített névvel rendelkező elem nem található.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az elem minősített neve. |

### Visszatérési érték

**true** ha a megfelelő elem megtalálható; egyébként **false**, és a [XmlReader](../) állapota a fájl vége.

## XmlReader::ReadToFollowing(String, String) metódus

Olvas addig, amíg a megadott helyi névvel és névtér-URI-val rendelkező elem nem található.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az elem helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az elem névtér-URI-ja. |

### Visszatérési érték

**true** ha a megfelelő elem megtalálható; egyébként **false**, és a [XmlReader](../) állapota a fájl vége.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)