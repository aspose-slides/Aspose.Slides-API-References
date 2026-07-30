---
title: Peek()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge un singolo carattere dal flusso senza modificare il cursore di lettura del flusso.
type: docs
weight: 27
url: /it/system.io/streamreader/peek/
---
## StreamReader::Peek() metodo


Legge un singolo carattere dal flusso senza modificare il cursore di lettura del flusso.

```cpp
virtual int System::IO::StreamReader::Peek() override
```


### Valore di ritorno

Carattere letto codificato con codifica UTF-16; se il carattere letto è rappresentato da due codepoint nella codifica UTF-16 allora viene restituita solo la surrogata alta; se non è stato letto alcun carattere viene restituito -1

## Vedi anche

* Classe [StreamReader](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)