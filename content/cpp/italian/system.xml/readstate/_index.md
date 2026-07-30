---
title: ReadState
second_title: Riferimento API Aspose.Slides per C++
description: Specifica lo stato del lettore.
type: docs
weight: 703
url: /it/system.xml/readstate/
---
## ReadState enum

Specifica lo stato del lettore.

```cpp
enum class ReadState
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Initial | 0 | Il metodo [XmlReader::Read](../xmlreader/read/) non è stato chiamato. |
| Interactive | 1 | Il metodo [XmlReader::Read](../xmlreader/read/) è stato chiamato. Metodi aggiuntivi possono essere chiamati sul lettore. |
| Error | 2 | Si è verificato un errore che impedisce il proseguimento dell'operazione di lettura. |
| EndOfFile | 3 | La fine del file è stata raggiunta con successo. |
| Closed | 4 | Il metodo [XmlReader::Close](../xmlreader/close/) è stato chiamato. |

## Vedi anche

* Spazio dei nomi [System::Xml](../)
* Libreria [Aspose.Slides](../../)