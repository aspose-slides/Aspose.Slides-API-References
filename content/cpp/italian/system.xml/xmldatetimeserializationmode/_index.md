---
title: XmlDateTimeSerializationMode
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica come trattare il valore temporale durante la conversione tra stringa e DateTime.
type: docs
weight: 781
url: /it/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Specifica come trattare il valore temporale durante la conversione tra stringa e [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Local | 0 | Tratta come ora locale. Se l'oggetto [DateTime](../../system/datetime/) rappresenta un Coordinated Universal Time (UTC), viene convertito all'ora locale. |
| Utc | 1 | Tratta come UTC. Se l'oggetto [DateTime](../../system/datetime/) rappresenta un'ora locale, viene convertito a UTC. |
| Unspecified | 2 | Tratta come ora locale se un [DateTime](../../system/datetime/) viene convertito in una stringa. Se una stringa viene convertita in [DateTime](../../system/datetime/), converti a ora locale se è specificato un fuso orario. |
| RoundtripKind | 3 | Le informazioni sul fuso orario dovrebbero essere preservate durante la conversione. |

## Vedi anche

* Spazio dei nomi [System::Xml](../)
* Libreria [Aspose.Slides](../../)