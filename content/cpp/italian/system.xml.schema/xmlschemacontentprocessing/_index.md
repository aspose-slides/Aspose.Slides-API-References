---
title: XmlSchemaContentProcessing
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce informazioni sulla modalità di convalida delle sostituzioni degli elementi any e anyAttribute.
type: docs
weight: 976
url: /it/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

Fornisce informazioni sulla modalità di convalida delle sostituzioni degli elementi **any** e **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Gli elementi del documento non vengono convalidati. |
| Skip | 1 | Gli elementi del documento devono essere XML ben formato e non vengono convalidati dallo schema. |
| Lax | 2 | Se lo schema associato viene trovato, gli elementi del documento verranno convalidati. Altrimenti non verranno generati errori. |
| Strict | 3 | Il processore dello schema deve trovare uno schema associato allo spazio dei nomi indicato per convalidare gli elementi del documento. |

## Vedi anche

* Spazio dei nomi [System::Xml::Schema](../)
* Libreria [Aspose.Slides](../../)