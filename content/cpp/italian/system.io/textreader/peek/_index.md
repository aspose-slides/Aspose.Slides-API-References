---
title: Peek()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge un singolo carattere dallo stream senza modificare il cursore di lettura dello stream.
type: docs
weight: 27
url: /it/system.io/textreader/peek/
---
## TextReader::Peek() metodo


Legge un singolo carattere dallo stream senza modificare il cursore di lettura dello stream.

```cpp
virtual int System::IO::TextReader::Peek()
```


### Valore di ritorno

Carattere letto codificato con codifica UTF-16; se il carattere letto è rappresentato da due codepoint nella codifica UTF-16 allora viene restituito solo il surrogato alto; se non è stato letto alcun carattere viene restituito -1

## Vedi anche

* Classe [TextReader](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)