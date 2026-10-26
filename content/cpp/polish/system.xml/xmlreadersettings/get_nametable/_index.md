---
title: get_NameTable()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca XmlNameTable używany do atomizowanych porównań ciągów znaków.
type: docs
weight: 1
url: /pl/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() metoda


Zwraca [XmlNameTable](../../xmlnametable/) używany do atomizowanych porównań ciągów znaków.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### Wartość zwracana

[XmlNameTable](../../xmlnametable/) przechowujący wszystkie atomizowane ciągi znaków używane przez wszystkie instancje [XmlReader](../../xmlreader/) utworzone przy użyciu tego obiektu [XmlReaderSettings](../). Domyślnie jest **nullptr**. Utworzona instancja [XmlReader](../../xmlreader/) użyje nowego pustego [NameTable](../../nametable/), jeśli ta wartość jest **nullptr**.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNameTable](../../xmlnametable/)
* Klasa [XmlReaderSettings](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)