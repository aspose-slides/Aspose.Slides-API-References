---
title: ReadNode()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří objekt XmlNode na základě informací v XmlReader. Čtečka musí být umístěna na uzel nebo atribut.
type: docs
weight: 495
url: /cs/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) metoda

Vytvoří objekt [XmlNode](../../xmlnode/) na základě informací v [XmlReader](../../xmlreader/). Čtečka musí být umístěna na uzel nebo atribut.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Zdroj XML. |

### Návratová hodnota

Nový [XmlNode](../../xmlnode/) nebo **nullptr**, pokud neexistují další uzly.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlReader](../../xmlreader/)
* Třída [XmlDocument](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)