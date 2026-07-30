---
title: get_NameTable()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací XmlNameTable používaný pro atomizované porovnávání řetězců.
type: docs
weight: 1
url: /cs/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() metoda

Vrací [XmlNameTable](../../xmlnametable/) používaný pro atomizované porovnávání řetězců.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Návratová hodnota

[XmlNameTable](../../xmlnametable/), který ukládá všechny atomizované řetězce použité všemi instancemi [XmlReader](../../xmlreader/) vytvořenými pomocí tohoto objektu [XmlReaderSettings](../). Výchozí hodnota je **nullptr**. Vytvořená instance [XmlReader](../../xmlreader/) použije nový prázdný [NameTable](../../nametable/), pokud je tato hodnota **nullptr**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNameTable](../../xmlnametable/)
* Třída [XmlReaderSettings](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)