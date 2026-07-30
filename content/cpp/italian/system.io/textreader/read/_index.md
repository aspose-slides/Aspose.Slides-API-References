---
title: Read()
second_title: Aspose.Slides per C++ Riferimento API
description: Legge un singolo carattere dal flusso.
type: docs
weight: 40
url: /it/system.io/textreader/read/
---
## TextReader::Read() metodo

Legge un singolo carattere dal flusso.

```cpp
virtual int System::IO::TextReader::Read()
```

### Valore di ritorno

Carattere letto codificato con codifica UTF-16; se il carattere letto è rappresentato da due punti di codice nella codifica UTF-16, viene restituito solo il surrogato alto.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) metodo

Legge il numero specificato di caratteri dal flusso e li scrive nell'array di caratteri specificato a partire dalla posizione specificata.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | L'array di caratteri UTF-16 in cui scrivere i caratteri letti dal flusso |
| index | int | Un indice basato su 0 in **buffer** a partire dal quale iniziare la scrittura |
| count | int | Il numero di caratteri da leggere dal flusso |

### Valore di ritorno

Il numero di caratteri letti dal flusso

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [TextReader](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)