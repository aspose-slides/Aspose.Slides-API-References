---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Generuje a zapisuje entitu náhradního znaku pro dvojici náhradních znaků.
type: docs
weight: 391
url: /cs/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) metoda


Generuje a zapisuje entitu náhradního znaku pro dvojici náhradních znaků.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lowChar | char16_t | Nízký surogát. To musí být hodnota mezi **0xDC00** a **0xDFFF**. |
| highChar | char16_t | Vysoký surogát. To musí být hodnota mezi **0xD800** a **0xDBFF**. |

## Viz také

* Třída [XmlTextWriter](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)