---
title: DtdProcessing
second_title: Riferimento API Aspose.Slides per C++
description: Specifica le opzioni per l'elaborazione dei DTD. L'enumerazione DtdProcessing è usata dalla classe XmlReaderSettings.
type: docs
weight: 638
url: /it/system.xml/dtdprocessing/
---
## DtdProcessing enum

Specifica le opzioni per l'elaborazione dei DTD. L'enumerazione DtdProcessing è usata dalla classe [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Prohibit | 0 | Specifica che quando un DTD viene incontrato, viene lanciata un'XmlException con un messaggio che indica che i DTD sono proibiti. Questo è il comportamento predefinito. |
| Ignore | 1 | Fa sì che l'elemento DOCTYPE venga ignorato. Non avviene alcuna elaborazione del DTD e il DTD/DOCTYPE viene perso in output. |
| Parse | 2 | Usato per l'analisi dei DTD. |

## Vedi anche

* Namespace [System::Xml](../)
* Libreria [Aspose.Slides](../../)