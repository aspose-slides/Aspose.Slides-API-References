---
title: get_NameTable()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja az atomizált karakterlánc-összehasonlításokhoz használt XmlNameTable-t.
type: docs
weight: 1
url: /hu/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() metódus


Visszaadja a [XmlNameTable](../../xmlnametable/)-t, amelyet atomizált karakterlánc-összehasonlításokhoz használnak.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### Visszatérési érték

A [XmlNameTable](../../xmlnametable/), amely tárolja az összes atomizált karakterláncot, amelyet az összes [XmlReader](../../xmlreader/) példány használ, a [XmlReaderSettings](../) objektum segítségével létrehozott. Az alapértelmezett érték **nullptr**. A létrehozott [XmlReader](../../xmlreader/) példány egy új üres [NameTable](../../nametable/)-t fog használni, ha ez az érték **nullptr**.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNameTable](../../xmlnametable/)
* Osztály [XmlReaderSettings](../)
* Névterület [System::Xml](../../)
* Library [Aspose.Slides](../../../)