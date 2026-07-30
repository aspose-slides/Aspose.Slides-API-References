---
title: FileMode
second_title: Aspose.Slides per C++ Riferimento API
description: Specifica come deve essere aperto un file.
type: docs
weight: 508
url: /it/system.io/filemode/
---
## FileMode enumerazione

Specifica come dovrebbe essere aperto un file.

```cpp
enum class FileMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| CreateNew | 1 | Crea un nuovo file. Se il file esiste già, viene generata un'eccezione. |
| Create | 2 | Crea un nuovo file. Se il file esiste già, viene sovrascritto. |
| Open | 3 | Apri un file esistente. Se il file non esiste, viene generata un'eccezione. |
| OpenOrCreate | 4 | Apri un file esistente o crea un nuovo file se non esiste. |
| Truncate | 5 | Apri un file esistente e lo tronca in modo che sia vuoto. Se il file non esiste, viene generata un'eccezione. |
| Append | 6 | Apri un file esistente e posizionati alla fine di esso o crea un nuovo file se non esiste. |

## Vedi anche

* Namespace [System::IO](../)
* Libreria [Aspose.Slides](../../)