---
title: PeekChar()
second_title: Aspose.Slides per C++ Riferimento API
description: Legge un singolo carattere dal flusso di input senza modificare il cursore di lettura del flusso.
type: docs
weight: 53
url: /it/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() method


Legge un singolo carattere dal flusso di input senza modificare il cursore di lettura del flusso.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```


### Valore di ritorno

Carattere letto codificato con codifica UTF-16; se il carattere letto è rappresentato da due punti di codice nella codifica UTF-16 viene restituito solo il surrogato alto; se non è stato letto alcun carattere viene restituito -1

## Vedi anche

* Classe [BinaryReader](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)