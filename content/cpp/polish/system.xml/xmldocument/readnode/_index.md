---
title: ReadNode()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Tworzy obiekt XmlNode na podstawie informacji zawartych w XmlReader. Czytnik musi być ustawiony na węzeł lub atrybut.
type: docs
weight: 495
url: /pl/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) metoda

Tworzy obiekt [XmlNode](../../xmlnode/) na podstawie informacji zawartych w [XmlReader](../../xmlreader/). Czytnik musi być ustawiony na węzeł lub atrybut.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Źródło XML. |

### Wartość zwracana

Nowy [XmlNode](../../xmlnode/) lub **nullptr**, jeśli nie istnieją już dalsze węzły.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlReader](../../xmlreader/)
* Klasa [XmlDocument](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)