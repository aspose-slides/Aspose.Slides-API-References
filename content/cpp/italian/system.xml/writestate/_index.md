---
title: WriteState
second_title: Riferimento API Aspose.Slides per C++
description: Specifica lo stato dello XmlWriter.
type: docs
weight: 755
url: /it/system.xml/writestate/
---
## WriteState enum

Specifica lo stato di [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Start | 0 | Indica che il metodo XmlWriter::Write non è ancora stato chiamato. |
| Prolog | 1 | Indica che il prologo è in fase di scrittura. |
| Element | 2 | Indica che un tag di inizio elemento è in fase di scrittura. |
| Attribute | 3 | Indica che un valore di attributo è in fase di scrittura. |
| Content | 4 | Indica che il contenuto dell'elemento è in fase di scrittura. |
| Closed | 5 | Indica che il metodo [XmlWriter::Close](../xmlwriter/close/) è stato chiamato. |
| Error | 6 | È stata sollevata un'eccezione, che ha lasciato [XmlWriter](../xmlwriter/) in uno stato non valido. È possibile chiamare il metodo [XmlWriter::Close](../xmlwriter/close/) per mettere [XmlWriter](../xmlwriter/) nello stato [WriteState::Closed](./). Qualsiasi altra chiamata al metodo [XmlWriter](../xmlwriter/) genera un InvalidOperationException. |

## Vedi anche

* Spazio dei nomi [System::Xml](../)
* Libreria [Aspose.Slides](../../)