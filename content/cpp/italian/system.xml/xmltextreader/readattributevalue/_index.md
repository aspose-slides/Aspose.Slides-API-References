---
title: ReadAttributeValue()
second_title: Riferimento API di Aspose.Slides per C++
description: Analizza il valore dell'attributo in uno o più nodi Text, EntityReference o EndEntity.
type: docs
weight: 560
url: /it/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() metodo

Analizza il valore dell'attributo in uno o più **[Text](../../../system.text/)**, **EntityReference**, o **EndEntity** nodi.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Valore di ritorno

**true** se ci sono nodi da restituire. **false** se il lettore non è posizionato su un nodo attributo quando viene effettuata la chiamata iniziale o se tutti i valori dell'attributo sono stati letti. Un attributo vuoto, ad esempio **misc=\"\"**, restituisce **true** con un singolo nodo con valore [String::Empty](../../../system/string/empty/).

## Vedi anche

* Classe [XmlTextReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)