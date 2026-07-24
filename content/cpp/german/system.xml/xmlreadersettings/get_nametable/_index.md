---
title: get_NameTable()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt die XmlNameTable zurück, die für atomisierte Zeichenfolgenvergleiche verwendet wird.
type: docs
weight: 1
url: /de/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() Methode


Gibt die [XmlNameTable](../../xmlnametable/) zurück, die für atomisierte Zeichenfolgenvergleiche verwendet wird.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### Rückgabewert

Das [XmlNameTable](../../xmlnametable/), das alle atomisierten Zeichenfolgen speichert, die von allen [XmlReader](../../xmlreader/)-Instanzen verwendet werden, die mit diesem [XmlReaderSettings](../)-Objekt erstellt wurden. Der Standardwert ist **nullptr**. Die erstellte [XmlReader](../../xmlreader/)-Instanz verwendet ein neues leeres [NameTable](../../nametable/), wenn dieser Wert **nullptr** ist.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNameTable](../../xmlnametable/)
* Klasse [XmlReaderSettings](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)