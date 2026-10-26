---
title: ReadAttributeValue()
second_title: Riferimento API di Aspose.Slides per C++
description: Analizza il valore dell'attributo in uno o più nodi Text, EntityReference o EndEntity.
type: docs
weight: 430
url: /it/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() metodo

Analizza il valore dell'attributo in uno o più nodi **[Text](../../../system.text/)**, **EntityReference**, o **EndEntity**.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Valore restituito

**true** se ci sono nodi da restituire. **false** se il lettore non è posizionato su un nodo attributo quando viene effettuata la chiamata iniziale o se tutti i valori degli attributi sono stati letti. Un attributo vuoto, ad esempio **misc=\"\"**, restituisce **true** con un singolo nodo con valore [String::Empty](../../../system/string/empty/).

## Vedi anche

* Classe [XmlNodeReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)