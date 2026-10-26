---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Při přepsání v odvozené třídě generuje a zapisuje entitu náhradního znaku pro dvojici náhradních znaků.
type: docs
weight: 261
url: /cs/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) metoda


Při přepsání v odvozené třídě generuje a zapisuje entitu náhradního znaku pro dvojici náhradních znaků.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lowChar | char16_t | Nízký náhradní znak. Musí být hodnota mezi 0xDC00 a 0xDFFF. |
| highChar | char16_t | Vysoký náhradní znak. Musí být hodnota mezi 0xD800 a 0xDBFF. |

## Viz také

* Třída [XmlWriter](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)