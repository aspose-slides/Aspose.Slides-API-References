---
title: get_NameTable()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de XmlNameTable die wordt gebruikt voor geatomiseerde tekenreeksvergelijkingen.
type: docs
weight: 1
url: /nl/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() methode

Retourneert de [XmlNameTable](../../xmlnametable/) die wordt gebruikt voor geatomiseerde tekenreeksvergelijkingen.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Retourwaarde

De [XmlNameTable](../../xmlnametable/) die alle geatomiseerde tekenreeksen opslaat die door alle [XmlReader](../../xmlreader/) instanties worden gebruikt die met dit [XmlReaderSettings](../) object zijn gemaakt. Standaard is **nullptr**. De gemaakte [XmlReader](../../xmlreader/) instantie zal een nieuwe lege [NameTable](../../nametable/) gebruiken als deze waarde **nullptr** is.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNameTable](../../xmlnametable/)
* Klasse [XmlReaderSettings](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)