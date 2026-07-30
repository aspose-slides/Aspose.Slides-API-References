---
title: get_NameTable()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce lo XmlNameTable utilizzato per i confronti di stringhe atomizzate.
type: docs
weight: 1
url: /it/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() metodo

Restituisce il [XmlNameTable](../../xmlnametable/) utilizzato per i confronti di stringhe atomizzate.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Valore di ritorno

Il [XmlNameTable](../../xmlnametable/) che memorizza tutte le stringhe atomizzate usate da tutte le istanze [XmlReader](../../xmlreader/) create usando questo oggetto [XmlReaderSettings](../). Il valore predefinito è **nullptr**. L'istanza [XmlReader](../../xmlreader/) creata utilizzerà un nuovo [NameTable](../../nametable/) vuoto se questo valore è **nullptr**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNameTable](../../xmlnametable/)
* Classe [XmlReaderSettings](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)