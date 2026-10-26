---
title: ReadAttributeValue()
second_title: Riferimento API Aspose.Slides per C++
description: Analizza il valore dell'attributo in uno o più nodi Text, EntityReference o EndEntity.
type: docs
weight: 508
url: /it/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() metodo

Parses il valore dell'attributo in uno o più nodi **[Text](../../../system.text/)**, **EntityReference** o **EndEntity**.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### Valore restituito

**true** se ci sono nodi da restituire. **false** se il lettore non è posizionato su un nodo attributo quando viene effettuata la chiamata iniziale o se tutti i valori degli attributi sono stati letti. Un attributo vuoto, ad esempio **misc=\"\"**, restituisce **true** con un singolo nodo con un valore di [String::Empty](../../../system/string/empty/).

## Vedi anche

* Classe [XmlValidatingReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)