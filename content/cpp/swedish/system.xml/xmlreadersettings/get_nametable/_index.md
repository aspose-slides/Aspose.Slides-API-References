---
title: get_NameTable()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar XmlNameTable som används för atomiserade strängjämförelser.
type: docs
weight: 1
url: /sv/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() metod

Returnerar den [XmlNameTable](../../xmlnametable/) som används för atomiserade strängjämförelser.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Returvärde

Den [XmlNameTable](../../xmlnametable/) som lagrar alla atomiserade strängar som används av alla [XmlReader](../../xmlreader/)-instanser som skapats med detta [XmlReaderSettings](../)-objekt. Standardvärdet är **nullptr**. Den skapade [XmlReader](../../xmlreader/)-instansen kommer att använda en ny tom [NameTable](../../nametable/) om detta värde är **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNameTable](../../xmlnametable/)
* Klass [XmlReaderSettings](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)