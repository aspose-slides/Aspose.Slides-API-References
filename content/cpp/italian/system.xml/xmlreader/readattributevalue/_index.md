---
title: ReadAttributeValue()
second_title: Riferimento API Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, analizza il valore dell'attributo in uno o più nodi Text, EntityReference o EndEntity.
type: docs
weight: 677
url: /it/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() metodo


Quando sovrascritto in una classe derivata, analizza il valore dell'attributo in uno o più **[Text](../../../system.text/)**, **EntityReference**, o **EndEntity** nodi.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### Valore restituito

**true** se ci sono nodi da restituire. **false** se il lettore non è posizionato su un nodo attributo quando viene effettuata la chiamata iniziale o se tutti i valori degli attributi sono stati letti. Un attributo vuoto, come **misc=\"\"**, restituisce **true** con un unico nodo con valore [String::Empty](../../../system/string/empty/).

## Vedi anche

* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)